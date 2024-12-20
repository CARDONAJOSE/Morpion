# **JEU DE MORPION**

## Introduction
Le Morpion est un jeu classique de stratégie pour deux joueurs, où chacun essaie d'aligner trois de ses symboles sur un plateau de 3x3. C'est un jeu simple mais captivant qui peut être joué n'importe où.

## Comment jouer ?

- **Plateau de jeu** : Un carré divisé en neuf cases égales.
- **Joueurs** : Deux joueurs s'affrontent, chacun choisissant un symbole : généralement, un "X" et un "O".
- **But du jeu** : Le premier joueur à aligner trois de ses symboles (horizontalement, verticalement ou diagonalement) gagne la partie.
- **Déroulement** : Les joueurs marquent à tour de rôle leur symbole dans une case vide. Si toutes les cases sont remplies sans qu'aucun joueur n'ait aligné trois symboles, la partie est nulle.

## Concepts clés utilisés :
- **Listes imbriquées** : Pour représenter le plateau.
- **Boucles** : Pour parcourir le plateau et gérer les tours.
- **Conditions** : Pour vérifier les conditions de victoire et les entrées utilisateur.
- **Fonctions** : Pour structurer le code et le rendre plus lisible.

## Mode d'emploi
1. Lancer le fichier `play_game.py`.
2. Entrer les coordonnées dans le terminal : deux entiers de 1 à 3 séparés par un espace, puis valider avec la touche `<entrée>`.
   - **Exemple** : Pour jouer dans la case du milieu, entrez `2 2`.
3. Répéter l'opération numéro 2 pour l'autre joueur jusqu'à la fin du jeu.

## Virtual environnement
```bash
python -m venv .venv
```
> .venv est le nom de l'environnement virtuel.

## Connect to the venv
- **mac/linux**: `source .venv/bin/activate.fish`
- **windows**: `.venv/Scripts/activate` ou `.venv/Scripts/activate.ps1`

## Créer requirements.txt à partir de pip
```bash
pip freeze > requirements.txt
```

## Installer les librairies dans un nouvel environnement
```bash
pip install -r requirements.txt
```

## Quitter l'environnement virtuel
```bash
deactivate
```

## Contribuer
Si vous souhaitez contribuer à ce projet, n'hésitez pas à soumettre une demande de tirage ou à ouvrir un problème.

## Licence
Ce projet est sous licence MIT. Voir le fichier LICENSE pour plus de détails.
