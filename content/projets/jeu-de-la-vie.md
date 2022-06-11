---
title: "Jeu de la vie"
date: 2022-05-04T16:48:24+02:00
images: ["/images/projets/conway.png"]
draft: false

---

# À propos du projet [Jeu de la vie](https://github.com/FACON-Nicolas/conways-life-game)

![](https://img.shields.io/badge/Release-v1.0-blueviolet)
![](https://img.shields.io/badge/Language-python-005255)
![](https://img.shields.io/badge/Libraries-pygame_pygame__gui-00cfff)
![](https://img.shields.io/badge/Size-2.4Mo-f12222)

Cet article contient le code source d’une copie d’un jeu de la vie développé en python à l’aide des bibliothèques pygame et pygame_gui

![](https://camo.githubusercontent.com/4ddd19aa3490eb63175806b9d4cf4b2a351772b58963fb207e045441de6a7dba/68747470733a2f2f692e6962622e636f2f715247726266772f636f6e776179732e706e67)

Le jeu de la vie est un jeu à automate cellulaire, le but du jeu est de donner une grille de cellules vivantes (couleur noire) et de cellules mortes (couleur blanches), et une fois la grille donnée, cette dernière va évoluer de sorte à donner vie ou tuer des cellules en fonction de ses voisines, une cellule : 
 - née ou reste en vie si elle possède 3 voisines vivantes
 - reste dans le même état si elle possède 2 voisines vivantes
 - meurt dans le reste des cas

![](https://www.fil.univ-lille1.fr/~L1S2API/CoursTP/_images/R123.jpg)

# Sommaire

* **[Sommaire](#sommaire)**
* **[Développeur](#developpeur)**
* **[Features](#features)**
* **[Controles](#contrôles)**
* **[Versions](#versions)**

# Developpeur

 + **[Facon Nicolas](https://www.github.com/FACON-Nicolas)**

# Features

Pour permettre la meilleure des utilisations de l'application, j'ai ajouté:
 + la visualisation de l'évolution étape par étape
 + la possibilité de revisionner une étape précédente
 + la possibilité de générer une grille aléatoire

# Versions 

**1.0.0** : création du projet.