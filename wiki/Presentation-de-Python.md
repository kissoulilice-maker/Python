# Présentation de Python

## 1. Origine

Python est un langage de programmation créé par **Guido van Rossum**. Sa première version publique est sortie en **1991**.

Son nom fait référence à la série humoristique britannique *Monty Python's Flying Circus*, et non directement au serpent.

## 2. Caractéristiques principales

Python est :

- **lisible** : sa syntaxe est conçue pour être facile à comprendre ;
- **polyvalent** : il est utilisé dans de nombreux domaines ;
- **multiplateforme** : il fonctionne sur plusieurs systèmes ;
- **open source** : son code source est accessible ;
- **riche en bibliothèques** : des modules ajoutent des fonctionnalités.

Il est utilisé pour le développement web, l'automatisation, l'intelligence artificielle, l'analyse de données, les réseaux et la cybersécurité.

## 3. Syntaxe simple

~~~python
print("Bonjour")
~~~

La fonction intégrée print() affiche une valeur dans la console.

## 4. L'indentation

L'indentation correspond aux espaces placés au début d'une ligne. En Python, elle définit les blocs d'instructions associés à if, else, aux boucles ou aux fonctions.

~~~python
age = 18

if age >= 18:
    print("Majeur")
else:
    print("Mineur")
~~~

Les lignes décalées sous if et else appartiennent à leurs blocs respectifs. Le mot-clé else est aligné avec if.

Une indentation incorrecte peut provoquer une erreur ou changer la logique du programme. Par convention, on utilise généralement **4 espaces** par niveau et on évite de mélanger tabulations et espaces.

### Comparaison avec le langage C

En C, les accolades délimitent généralement les blocs :

~~~c
if (age >= 18) {
    printf("Majeur");
}
~~~

En Python, c'est l'indentation qui joue ce rôle.

## 5. Le typage dynamique

Python détermine automatiquement le type associé à une valeur. Il n'est généralement pas nécessaire de déclarer le type lors de la création d'une variable.

~~~python
age = 18       # entier (int)
nom = "Alex"   # chaîne de caractères (str)
prix = 9.99    # nombre décimal (float)
actif = True   # booléen (bool)
~~~

Le type d'une valeur peut être vérifié avec type() :

~~~python
print(type(age))
~~~

Le typage dynamique ne signifie pas que les types n'ont aucune importance : certaines opérations ne sont pas compatibles entre elles.

## 6. Les bibliothèques

Une bibliothèque regroupe du code réutilisable. Python possède une bibliothèque standard intégrée et permet aussi d'installer des bibliothèques externes avec pip.

Exemples :

- **socket** : communications réseau ;
- **hashlib** : fonctions de hachage ;
- **requests** : requêtes HTTP vers des services Web ;
- **scapy** : manipulation et analyse de paquets réseau.

Leurs usages sont détaillés dans [Python et cybersécurité](Python-et-cybersecurite.md).

## 7. À retenir

Python se distingue par sa syntaxe lisible, son indentation significative, son typage dynamique et ses nombreuses bibliothèques.
