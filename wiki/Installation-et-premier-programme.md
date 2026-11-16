# Installation et premier programme

Cette page reprend le parcours d'installation du guide initial et précise les vérifications à effectuer.

## 1. Installer Python

Téléchargez Python depuis le [site officiel](https://www.python.org/downloads/) et suivez les étapes adaptées à votre système.

Sous Windows, l'option permettant d'ajouter Python au PATH peut être utile pour lancer Python depuis le terminal.

Vérifiez l'installation :

~~~bash
python --version
~~~

Selon le système, la commande peut être python3 --version (macOS/Linux) ou py --version (Windows).

## 2. Installer Visual Studio Code

Téléchargez [Visual Studio Code](https://code.visualstudio.com/) depuis le site officiel, puis installez-le.

VS Code est un éditeur de code qui permet d'organiser les fichiers, d'écrire des programmes et d'utiliser un terminal intégré.

## 3. Installer l'extension Python

1. Ouvrez VS Code.
2. Accédez à l'onglet **Extensions**.
3. Recherchez **Python**.
4. Installez l'extension publiée par **Microsoft**.
5. Ouvrez ou créez un fichier portant l'extension .py.

L'extension apporte notamment l'aide à la saisie, la sélection de l'interpréteur et des fonctions de débogage. Elle ne remplace pas l'installation de Python : l'interpréteur doit être installé séparément.

## 4. Créer le premier projet

Créez un dossier nommé hello_world, puis ouvrez-le dans VS Code.

À l'intérieur, créez un fichier nommé hello.py et ajoutez :

~~~python
print("Hello World")
~~~

Enregistrez le fichier.

## 5. Exécuter le programme

Ouvrez le terminal intégré avec **Terminal > Nouveau terminal**. Vérifiez que le terminal se trouve dans le dossier contenant hello.py, puis lancez :

~~~bash
python hello.py
~~~

Selon le système, utilisez si nécessaire python3 hello.py ou py hello.py.

Résultat attendu :

~~~text
Hello World
~~~

## 6. Vérifier le fonctionnement

Si le texte attendu apparaît, le fichier a bien été exécuté par l'interpréteur Python.

En cas de problème, vérifiez :

- que le fichier s'appelle bien hello.py ;
- que le terminal est ouvert dans le bon dossier ;
- que Python est installé ;
- que la commande utilisée correspond à votre système ;
- que le code est enregistré.

## 7. Captures d'écran

Vous pouvez ajouter des captures montrant l'installation de Python, VS Code et de l'extension, la commande de vérification de version, le contenu de hello.py et le résultat de son exécution.

[Retour à l'accueil du wiki](Home.md)
