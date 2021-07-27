
Voici le déroulement du programme à l'execution.

A l’exécution, le programme affiche un message à l'utilisateur indiquant de choisir la profondeur de l'IA (un entier)
Par la suite l'utilisation d'un Elagage ou non est proposé.
Saisir 0 pour ne pas utiliser d'élagage ou saisir 1 pour l'utiliser. 

Lorsque la saisie est valide, la grille du jeu est initialisée avec les quatre pions situés dans les
angles.
La grille du jeu est affichée, le joueur courant exécute un coup valide celui-ci est affiché sur
la console suivis de la liste des coups étant valide pour ce joueur.
La grille du jeu actuelle et celle actualisé sont alors affichées avec le score et nom de chaque
joueur.
L’affichage de la grille de jeu est une chaine de caractère contenant :
• Un “B” qui représente les pions bleus
• Un “.” qui représente les cases vide
• Un “R” qui représente les pions rouges
En fin de jeu le score est également affiché suivis du nom du gagnant, du nombre de nœud
parcouru pour chaque joueur ainsi que le nom de l’IA utilisée


Pour la compilation voici les lignes de codes du fichier bash(en considérent que le dossier games existe). 
#!/bin/sh
javac -d build src/games/*.java
java -cp build games/Main


Les deux dernières lignes peuvent être executer seul dans le terminal.
Bon jeu à vous.