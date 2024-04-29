# Notes détaillées sur la Cryptographie

## 1. Introduction à la Cryptographie
- La cryptographie est l'art de sécuriser les communications en transformant des données en un format illisible, appelé chiffrement, afin qu'elles ne puissent être comprises que par les parties autorisées.
- Son utilisation remonte à l'Antiquité, avec des exemples comme le chiffrement César utilisé par Jules César.
- La cryptographie moderne repose sur des algorithmes mathématiques complexes et des protocoles sécurisés pour garantir la confidentialité, l'intégrité, l'authentification et la non-répudiation des données.

## 2. Principes de base
- **Confidentialité** : Assurer que seules les parties autorisées peuvent accéder aux informations.
- **Intégrité** : Garantir que les données n'ont pas été altérées ou modifiées en transit.
- **Authentification** : Vérifier l'identité des parties impliquées dans une communication.
- **Non-répudiation** : Empêcher qu'une partie puisse nier son implication dans une communication ou une transaction.

## 3. Chiffrement Symétrique
- Utilise une seule clé pour chiffrer et déchiffrer les données.
- Exemples d'algorithmes : AES (Advanced Encryption Standard), DES (Data Encryption Standard), 3DES (Triple DES).
- La principale préoccupation est la distribution sécurisée de la clé secrète entre les parties.

## 4. Chiffrement Asymétrique
- Utilise une paire de clés, une publique et une privée, pour chiffrer et déchiffrer les données.
- La clé publique est partagée et utilisée pour chiffrer les données, tandis que la clé privée est gardée secrète et utilisée pour déchiffrer les données.
- Exemples d'algorithmes : RSA (Rivest-Shamir-Adleman), ECC (Elliptic Curve Cryptography).
- Également utilisé pour la signature numérique, garantissant l'authenticité et la non-répudiation des données.

## 5. Protocoles de Sécurité
- **SSL/TLS (Secure Sockets Layer/Transport Layer Security)** : Protocoles de sécurité utilisés pour sécuriser les communications sur Internet, notamment les transactions financières, les sessions de messagerie et les connexions VPN.
- Utilise une combinaison de chiffrement symétrique et asymétrique pour garantir la confidentialité, l'intégrité et l'authentification des données.

## 6. Attaques Cryptographiques
- **Attaques par Force Brute** : Tentatives répétées pour deviner une clé en essayant toutes les combinaisons possibles.
- **Attaques par Collision** : Trouver deux entrées différentes qui produisent le même résultat de hachage, compromettant ainsi l'intégrité des données.
- D'autres attaques incluent la cryptanalyse différentielle, la cryptanalyse linéaire et les attaques par canaux cachés.

La cryptographie joue un rôle crucial dans la sécurisation des communications et des données numériques, offrant des mécanismes robustes pour garantir la confidentialité, l'intégrité, l'authentification et la non-répudiation des informations sensibles.
