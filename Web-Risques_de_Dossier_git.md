# Chapitre : Risques de Dossier .git

## 1. Risques de Dossier .git

### 1.1 Présentation
- Un dossier `.git` à la racine d'un serveur web peut contenir des informations sensibles sur le code source, l'historique des commits et les configurations du projet.
- Exposition du contenu de ce dossier peut entraîner des fuites d'informations critiques pour les attaquants.

### 1.2 Risques Potentiels
- **Fuite de Code Source** : Exposition du code source complet du projet, y compris les secrets, les clés d'API et les informations de connexion à la base de données.
- **Fuite d'Historique des Commits** : Révélation des modifications précédentes du code, permettant aux attaquants d'identifier les vulnérabilités et les failles corrigées.
- **Fuite de Configurations Sensibles** : Exposition des fichiers de configuration contenant des informations sensibles telles que les paramètres de base de données ou les clés d'authentification.

### 1.3 Mesures de Protection
- **Restriction d'Accès** : Restreindre l'accès au dossier `.git` en utilisant des règles de configuration du serveur web pour empêcher l'accès direct depuis le navigateur.
- **Suppression des Fichiers Sensibles** : Supprimer les fichiers sensibles, tels que les fichiers de configuration contenant des informations sensibles, du dépôt Git avant de le déployer sur un serveur web.
- **Audit de Sécurité** : Effectuer régulièrement des audits de sécurité pour détecter les fuites potentielles d'informations sensibles et les corriger rapidement.

#### exemple d'attaque
Un outil formidable pour réaliser cette attaque est [GitDumper](https://github.com/internetwache/GitTools/tree/master/Dumper). La documentation est très bien fournie.  
Une fois avec le dossier .git en notre possession nous pouvons lister les commits et même voir les modification apportés par chacun d'entre eux:
- premièrement on liste les commits avec la commande **git log** 
- deuxièmement si on repère un commit intéressant on peut avoir plus de détail avec la commande **git show id_commit**

La compréhension des risques liés aux attaques web telles que l'injection SQL et XSS, ainsi que la sensibilisation aux dangers associés à l'exposition d'un dossier `.git`, sont essentielles pour maintenir la sécurité des applications web et des infrastructures informatiques.
