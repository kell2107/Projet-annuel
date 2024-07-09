# Projet-annuel

Projet de création d'un jeu 


# Objectif
Ce dépot à pour but de créer un jeu ou les étudiants doivents créer une IA qui est difficile à battre.



![image](https://github.com/kell2107/Projet-annuel/assets/118818048/cc44beb3-9faa-49eb-88a1-7b41c14ccfc5)






# Fonctionnement 
Le but de ce jeu est de gagner soit en marquant des points indiquer sur la carte ou en prennant les pions adverses. Le plateau dispose de 14 pions (7 pions pour les deux joueurs). Le jeu oppose les pions bleu (joueur) contre les pions rouge (IA). Lorsqu'on lancera le jeu, il placera aléatoirement sur la carte 4 point à atteindre pour gagner la partie ou en prennant les pions adverses :

3 point doré = 1 point

1 point jaune = 3 point


Le pion : Les pions ne se déplacent que d'une case mais peuvent aller dans toutes les directions (devant, derrière, diagonale, horizontale, vertitale, en haut, en bas). Les pions ont 2 points de vie (pv) et pour faire baisser leurs pv, il faut pousser le pion adversaire deux fois seulement alors il perdra 1 pv, ou il est possible de prendre le pion adversaire en blocand le pion adverse et il sera considéré mort. Une fois que le pion adverse à été poussé, il sera dans l'incapacité de pouvoir bouger au prochain tour.


# Amélioration du code pour l'IA et le jeu
Les améliorations que nous avons apporté pour que l'IA soit plus performante et plus difficile à battre nous avons ajouté plusieurs fonctions :

1) une fonction qui priviligie l'attaque si l'ennemie est proche
2) une fonction qui vise tout les points sur la carte
3) fonction d'un temps de pour prendre une décision pour jouer
4) fonction qui affiche le déplacement des pions de l'IA
5) fonction qui quand on appuie sur la barre espace on passe le tour à l'adversaire
6) bouton pour quitter ou rejouer



