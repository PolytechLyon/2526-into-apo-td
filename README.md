# Conversion d'un graphe au format dot

Dans cet exercice, vous allez réaliser une application Java qui convertit un graph donnée dans un format décrit
ci-dessous, à un format dot.

## Modalités
* Cet exercice ne sera pas noté.
* Il est à réaliser en binôme.
* Sauf exception, approuvée par l'enseignant, vous ne devez pas réaliser cet exercice seul.

## Format de fichier d'entrée
Le fichier `input.txt` décrit des connexions par train entre différentes villes.
Il a le format suivant :
1. Une liste des noms de toutes les villes desservies. Les noms sont séparés par des retours à la ligne.
2. Une ligne vide séparant les noms de villes de leurs connexions.
3. Une liste des connexions entre les villes. Les connexions sont séparés par des retours à la ligne.
Chaque connexion est un triplet des élements suivants, dans l'ordre :
   * L'index de la ville de départ, dans la liste des villes, en commençant à zéro,
   * L'index de la ville de destination, dans la liste des villes, en commençant à zéro,
   * La durée de trajet en heure.

### Format cible
Le fichier de sortie doit avoir [le format dot](https://fr.wikipedia.org/wiki/DOT_(langage)) compris par des outils tels
que `graphvis`.

Vous pouvez tester votre format de sortie sur
(ce site d'affichage des graphes en format dot)[https://dreampuf.github.io/GraphvizOnline/].

### Lecture de nom de fichier d'entrée
Dans ce dépôt de code, un fichier d'entrée est fourni à titre d'exemple. Toutefois, le nom du fichier d'entrée peut
varier selon les besoins de l'utilisateur.

Il est donc recommandé que votre application accepte un argument en ligne de commande permettant de spécifier le nom du
fichier d'entrée à utiliser.

### Préconisation
Ce dépot de code utilise l'outil de compilation `maven` et il est configuré d'utiliser le dossier `src` pour accueillir
le code source. Vous êtes invités à réspecter cette configuration.









