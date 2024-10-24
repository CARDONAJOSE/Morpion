# **JEU DE MORPION**

**Comment jouer ?**

- Plateau de jeu : Un carré divisé en neuf cases égales.
- Joueurs : Deux joueurs s'affrontent, chacun choisissant un symbole : généralement, un "X" et un "O".
- But du jeu : Le premier joueur à aligner trois de ses symboles (horizontalement, verticalement ou diagonalement) gagne la partie.
- Déroulement : Les joueurs marquent à tour de rôle leur symbole dans une case vide. Si toutes les cases sont remplies sans qu'aucun joueur n'ait aligné trois symboles, la partie est nulle.

**Concepts clés utilisés :**
- Listes imbriquées : Pour représenter le plateau.
- Boucles : Pour parcourir le plateau et gérer les tours.
- Conditions : Pour vérifier les conditions de victoire et les entrées utilisateur.
- Fonctions : Pour structurer le code et le rendre plus lisible.
## Mode d'emploi
1. Lancer le fichier `play_game.py`.
2. Entrer les coordonnées dans le terminal : deux entiers de 1 à 3 séparés par un espace, puis valider avec la touche `<entrée>`.
3. Répéter l'opération numéro 2 pour l'autre joueur jusqu'à la fin du jeu.

**Virtual environnement**
```bash
python -m venv .venv
```
> .venv is the name of the virtual environnement 

**Connect to the venv** 

- mac/linux
`source .venv/bin/activate.fish`
- windows
`.venv/Scripts/activate` or `.venv/Scripts/activate.ps1` 

**create requirements.txt from pip**
`pip freeze > requirements.txt`

in a new environnement install the librairies
**install librairies**
`pip install -r requirements.txt`

**quit venv**
`deactivate`
 
