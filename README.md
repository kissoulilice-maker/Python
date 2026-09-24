# Python

## 1. Présentation de Python

Python est un langage de programmation créé par **Guido van Rossum**.
Sa première version publique est sortie en **1991**.

Python est un langage :

- simple à apprendre ;
- lisible ;
- polyvalent ;
- multiplateforme ;
- open source.

Il est utilisé dans de nombreux domaines comme :

- le développement web ;
- l'intelligence artificielle ;
- l'analyse de données ;
- l'automatisation ;
- les réseaux ;
- la cybersécurité.

---

## 2. Les particularités de Python

Python possède plusieurs caractéristiques qui le rendent particulier
par rapport à d'autres langages de programmation.

### 2.1 Une syntaxe simple et lisible

Python possède une syntaxe relativement simple. Il permet souvent
d'effectuer une tâche avec moins de code que certains autres langages.

Par exemple :

```python
print("Hello World")
```

Cette seule instruction permet d'afficher le texte « Hello World ».

Cette simplicité rend le code plus facile à lire et à comprendre.

---

### 2.2 L'indentation

Une des grandes particularités de Python est que **l'indentation fait
partie de la syntaxe du langage**.

L'indentation correspond aux **espaces placés au début d'une ligne**.

Elle permet à Python de comprendre quelles instructions appartiennent
à un même bloc de code.

Par exemple :

```python
age = 18

if age >= 18:
    print("La personne est majeure")
    print("Elle a 18 ans ou plus")
else:
    print("La personne est mineure")
```

Dans cet exemple, les deux instructions `print()` situées sous le `if`
sont décalées vers la droite.

Elles appartiennent donc au bloc de code du `if`.

Le `else` est placé au même niveau que le `if`, car il correspond à
cette condition.

### Pourquoi l'indentation est-elle importante ?

En Python, une mauvaise indentation peut provoquer une erreur ou modifier
le fonctionnement du programme.

Exemple correct :

```python
if age >= 18:
    print("Majeur")
```

La ligne `print()` est indentée et appartient donc au `if`.

Exemple incorrect :

```python
if age >= 18:
print("Majeur")
```

Ici, `print()` n'est pas indenté alors qu'il devrait l'être.
Python va donc générer une erreur.

### Python comparé à d'autres langages

Dans des langages comme **C, C++ ou Java**, les blocs de code sont
généralement délimités par des accolades `{ }`.

Exemple en C :

```c
if (age >= 18) {
    printf("Majeur");
}
```

En Python, les accolades ne sont pas nécessaires pour définir le bloc :

```python
if age >= 18:
    print("Majeur")
```

L'indentation permet donc de rendre la structure du programme
directement visible.

---

### 2.3 Le typage dynamique

Python utilise le **typage dynamique**.

Il n'est généralement pas nécessaire de préciser le type d'une variable
lors de sa création.

Exemple :

```python
age = 18
nom = "Alex"
```

Python détermine automatiquement le type de chaque valeur.

Cela permet d'écrire du code plus rapidement, même si le programmeur
doit toujours faire attention aux types utilisés.

---

### 2.4 Un grand nombre de bibliothèques

Python possède un très grand écosystème de bibliothèques.

Elles permettent d'ajouter facilement des fonctionnalités dans un
programme.

Il existe des bibliothèques pour :

- le développement web ;
- les réseaux ;
- l'intelligence artificielle ;
- l'analyse de données ;
- l'automatisation ;
- la cybersécurité.

---

## 3. Origine du nom Python

Le nom **Python** ne vient pas directement du serpent.

Le créateur du langage, **Guido van Rossum**, était un amateur de la
série humoristique britannique **Monty Python's Flying Circus**.

Il a choisi le nom **Python** en référence à cette série.

Le nom du langage possède donc une origine **humoristique et culturelle**.

---

## 4. Utilité de Python en cybersécurité

Python est très utilisé dans le domaine de la **cybersécurité**.

Il permet notamment :

- d'automatiser certaines tâches ;
- d'analyser des fichiers ;
- d'analyser des journaux système ;
- de travailler avec les réseaux ;
- de traiter des données ;
- de créer des outils de sécurité ;
- d'effectuer des tests de sécurité dans un environnement autorisé.

Python est particulièrement intéressant en cybersécurité car il permet
d'automatiser rapidement des tâches répétitives.

### Quelques bibliothèques utilisées en cybersécurité

#### `socket`

La bibliothèque `socket` permet de réaliser des communications réseau
entre différents programmes ou ordinateurs.

#### `requests`

La bibliothèque `requests` permet de communiquer facilement avec des
services Web.

#### `scapy`

La bibliothèque `scapy` permet de manipuler et d'analyser des paquets
réseau.

#### `hashlib`

La bibliothèque `hashlib` permet d'utiliser différentes fonctions de
hachage.

---

## 5. Choix de l'IDE

Pour développer en Python, j'ai choisi **Visual Studio Code (VS Code)**.

VS Code est un éditeur de code développé par Microsoft.

J'ai choisi cet IDE car :

- il est gratuit ;
- il fonctionne sous Windows, Linux et macOS ;
- il est léger ;
- il possède un terminal intégré ;
- il permet d'installer des extensions ;
- il prend en charge plusieurs langages ;
- il est adapté au développement Python.

---

## 6. Installation de l'environnement

Pour utiliser Python, j'ai d'abord installé **Python** sur mon ordinateur.

J'ai ensuite installé **Visual Studio Code**.

Dans VS Code, j'ai installé l'extension **Python** publiée par Microsoft.

Cette extension permet notamment :

- d'exécuter des programmes Python ;
- d'avoir de l'autocomplétion ;
- de détecter certaines erreurs ;
- de déboguer les programmes.

La procédure détaillée d'installation se trouve dans le fichier
`installation.md`.

---

## 7. Test de l'environnement : Hello World

Pour tester mon environnement de travail, j'ai créé un fichier appelé
`hello.py`.

J'ai écrit le programme suivant :

```python
print("Hello World")
```

J'ai ensuite exécuté le programme avec la commande :

```bash
python hello.py
```

Le résultat obtenu est :

```text
Hello World
```

Ce test permet de vérifier que Python, VS Code et l'environnement de
développement fonctionnent correctement.

---

## 8. Conclusion

Python est un langage de programmation simple, lisible et polyvalent.

Ses principales particularités sont notamment :

- sa syntaxe simple ;
- son système d'indentation ;
- son typage dynamique ;
- son grand nombre de bibliothèques ;
- sa polyvalence.

Son utilisation dans les réseaux, l'automatisation et la cybersécurité
en fait également un langage intéressant pour les professionnels de
l'informatique.

Le programme **Hello World** permet de vérifier que l'environnement de
développement est correctement installé et fonctionnel.
