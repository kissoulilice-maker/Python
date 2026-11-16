# IDE et outils de développement

## 1. Qu'est-ce qu'un IDE ?

Un IDE (*Integrated Development Environment*, ou environnement de développement intégré) regroupe plusieurs outils destinés à faciliter la programmation : éditeur, terminal, aide à la saisie et outils de débogage.

VS Code est plus précisément un éditeur de code extensible. Avec ses extensions, il peut proposer des fonctions proches de celles d'un IDE.

## 2. Pourquoi utiliser Visual Studio Code ?

Le projet utilise **Visual Studio Code (VS Code)**, développé par Microsoft.

Ce choix s'explique notamment par :

- sa gratuité ;
- sa disponibilité sur Windows, Linux et macOS ;
- son terminal intégré ;
- son système d'extensions ;
- la prise en charge de nombreux langages ;
- ses outils d'aide à l'écriture et au débogage.

## 3. L'extension Python

L'extension Python publiée par Microsoft ajoute des fonctions utiles pour travailler sur les fichiers .py :

- aide à la saisie et navigation dans le code ;
- sélection de l'interpréteur Python ;
- exécution et débogage ;
- intégration avec d'autres outils Python compatibles.

Il faut distinguer **Python**, qui exécute le programme, de **VS Code**, qui sert à écrire et organiser le code.

## 4. Le terminal

Le terminal permet de saisir des commandes. Il est utilisé ici pour vérifier la version de Python et lancer le programme :

~~~bash
python --version
python hello.py
~~~

La commande peut varier selon le système : python3 ou py peuvent être nécessaires.

[Voir le guide d'installation et le premier programme](Installation-et-premier-programme.md)
