Cahier de suivi de projet de Quentin Garnier
==

Première séance : mise en place du projet (18 décembre 2017)
--
Nous avons, durant cette séance, définit quel sera notre projet et commencé à réfléchir à la distribution des tâches et au matériel qui nous sera nécessaire pour mener à bien la construction de nos consoles de jeu.
Nous avons donc déjà rassemblé les idées d'utiliser la carte Arduino, un accéléromètre, un écran, des boutons poussoirs (x9), des circuits imprimés et une batterie Lithium.

Deuxième séance : début du projet (8 janvier 2018)
--
Cette fois-ci, nous avons commencé par rechercher le matériel de base essentiel à la conception de notre projet : nous somme tout d'abord partit sur une carte Arduino Mega ainsi qu'un écran TFT, puis nous avons longtemps pensé à la problématique du code à implémenter.
Nos principaux soucis étaient l'utilisation de Processing ou Arduino (ou les deux) : comment gérer leur mise en relation si l'on utilise les deux, comment faire les fonctions analogiques de l'Arduino via Processing ou comment implémenter les fonctions graphiques de Processing depuis Arduino.
A la fin de la séance, nous avions déjà plus cerné une problématique importante du sujet.

Troisième séance : passage à la Raspberry PI (15 janvier)
--
Ce jour-là, nous avions décidé d'emblée de choisir plutôt une carte Raspberry Pi 3, pour faciliter le tout, puisque notre console a pour but le jeu : néanmoins, nous pensons tout de même utiliser une carte Arduino pour ce qui est le traitement des composants électroniques tels que l'accéléromètre.
Nous avons donc commandé un écran adéquat, puisqu'il n'y en avait pas de disponible. Nous n'avons donc pas pu commencer à tester sans l'écran, mais nous avons déjà créer un petit programme de jeu.

Quatrième séance (22 janvier)
--
Nous avons passé l'heure à chercher des composants sur Internet, principalement un écran ainsi que les boutons poussoirs. Nous avions repéré plusieurs articles intéressants.
Faute de carte SD et d'écran, nous n'avions rien pu commencé d'autre. J'ai un peu commencé à coder des jeux.

Cinquième séance (7 février)
--
Nous avons commandé l'écran LCD 3.5 pouces, et nous avons en attendant testé la carte avec un écran temporaire, beaucoup trop grand. Cependant nous avons été confronté à de nombreux problèmes d'affichage : en effet, l'écran ne marchait tout simplement pas.
Nous avons perdu pas mal de temps à essayé de régler ce souci, ainsi que celui de la carte SD qui avait quelques problèmes également.

Sixième séance (14 février)
--
Premiers tests de la carte avec Ubuntu concluants : nous avons pu tester un premier programme Processing simple. Malheuresement, des problèmes de résolution nous ont ralentis.

Septième séance (21 mars)
--
Nous avons tenté de résoudre nos problèmes de résolution, malgré les deux échecs des tentatives précédentes durant les vacances : nous avons cette fois-ci testé de modifier les fichiers du BOOT de la carte Raspberry directement. Nous sommes parvenus à un résultat, cependant l'axe des abscisses été inversé, ce qui posait un nouveau problème.

Huitième séance (28 mars)
--
Le problème d'axe a été résolu en réinstallant d'une nouvelle façon le système Ubuntu Mate ainsi qu'une résolution d'écran plus adaptée. Le tactile fonctionne bien, et l'affichage est bon. Cependant le Bluetooth ne fonctionne plus correctement et le clavier sans fil que nous utilisions est devenu inutile ; nous avons donc dû nous débrouiller sans.

Neuvième séance (5 avril)
--
Les problèmes sont revenus de plus belle : après quelques utilisations de la carte, la barre d'outils en haut de l'écran a disparue. Il est donc devenu impossible de faire certaines choses, notamment les réglages qui nous permettaient de débugguer le bluetooth, ce qui nous a définitivement empêché d'utiliser le clavier sans fil.

Dixième séance (10 avril)
--
Nous avons réussit à lancer Processing sans la barre d'outils qui a disparue, et avons testé le code test pour les boutons poussoirs que nous avons reliés à la Raspberry, après avoir recherché comment les brancher sur les picots de l'écran : nous y sommes parvenu et le résultat a été concluant.

Onzième séance (4 mai)
--
Nous avons principalement essayé de débugguer le reste du programme, malheureusement sans succès. Nous avons donc dû faire avec. Nous avons également testé le jeu du Pong et l'affichage paraît correct.

Douzième séance (14 mai)
--
Les boutons poussoirs commandés sont arrivés, nous avons donc fait les branchements. Les fils avaient déjà été soudés à la platine. Enfin, on a modéliser avec un logiciel l'emballage de la carte, qui constituera la corps de la console dans lequel sera mis le matériel électronique. Nous avons également revus nos objectifs vu l'importante perte de temps due aux problèmes sur la Raspberry.
