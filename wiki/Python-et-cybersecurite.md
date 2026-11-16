# Python et cybersécurité

Python est apprécié en cybersécurité parce qu'il permet de traiter des données, d'automatiser des tâches et de communiquer avec des systèmes informatiques.

Les manipulations doivent être réalisées uniquement sur ses propres équipements ou dans un environnement de test pour lequel on dispose d'une autorisation.

## 1. Exemples d'utilisation

Python peut servir à :

- analyser des fichiers et des journaux système (logs) ;
- automatiser des tâches répétitives d'administration ;
- traiter des données ;
- communiquer avec des services Web ;
- comprendre et analyser des échanges réseau ;
- vérifier l'intégrité de fichiers ;
- développer des outils de diagnostic et de défense.

## 2. Bibliothèques à connaître

### socket

La bibliothèque standard socket permet à des programmes de communiquer sur un réseau. Elle aide à comprendre les notions de client, serveur, adresse IP et port.

### hashlib

La bibliothèque standard hashlib donne accès à des fonctions de hachage comme SHA-256. Un hachage produit une empreinte à partir de données. Il peut servir à comparer l'intégrité de fichiers.

~~~python
import hashlib

message = "Bonjour"
empreinte = hashlib.sha256(message.encode("utf-8")).hexdigest()

print(empreinte)
~~~

Le hachage n'est pas du chiffrement : il n'est pas conçu pour retrouver le texte d'origine à partir de l'empreinte.

### requests

La bibliothèque externe requests simplifie l'envoi de requêtes HTTP vers des services Web. Elle peut servir à récupérer des informations depuis une API autorisée.

### scapy

La bibliothèque externe scapy permet de représenter, lire et analyser des paquets réseau. Elle est utilisée pour l'apprentissage des protocoles et l'analyse dans des laboratoires autorisés.

## 3. Bibliothèque standard ou externe ?

- socket et hashlib font partie de la bibliothèque standard de Python.
- requests et scapy sont des bibliothèques externes à installer séparément si elles sont utilisées.

## 4. Bonnes pratiques

- Travailler uniquement sur des systèmes que l'on possède ou pour lesquels on a une autorisation explicite.
- Préférer un laboratoire isolé pour les exercices réseau.
- Ne pas enregistrer de mots de passe ou de clés secrètes directement dans le code.
- Vérifier les données reçues avant de les traiter.
- Lire la documentation officielle des bibliothèques utilisées.

## 5. À retenir

Python est un outil polyvalent pour l'analyse, l'automatisation et l'apprentissage des réseaux. En cybersécurité, son utilisation doit rester encadrée, légale et orientée vers la protection des systèmes.

[Retour à l'accueil du wiki](Home.md)
