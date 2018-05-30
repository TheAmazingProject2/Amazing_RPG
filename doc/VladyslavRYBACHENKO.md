Cahier de suivi de projet de Vladyslav Rybachenko
==

Première séance : mise en place (25/12/17)
--
Les idées différentes proposées et le choix définitif du projet qui est une console de jeu portable.

Deuxième séance (08/01/18)
--
Au cours de la première séance nous avons discuté de la forme de la console ainsi que des jeux qui seront disponible là-dessus. L'idée est d'effectuer le project grâce à la carte Arduino Mega et l'écran LCD qui nous ont été donnés pendant la séance. Nous avons aussi fait des recherches sur Internet sur la possibilité d'utilisation du code Processing (avec lequel les jeux sont codés) avec la carte Arduino Mega. De plus, on a cherché l'information sur comment brancher l'écran LCD sur la carte Arduino. 

Troisième séance (15/01/18)
--
Suite à des nombreuses recherches sur Internet on a compris que la carte Arduino Mega n'est pas assez puissante pour une console et peu compatible avec le code Procesing. On a donc décidé d'utiliser une carte Raspberry Pi dont la fréquence est d'environ 1 GHz au lieu de 16 MHz pour la carte Arduino Mega. Le reste de la séance a servi pour rechercher un écran LCD de la taille nécessaire et qui est compatible avec la carte donnée.    

Quatrième séance (22/01/18)
--
En raison du manque de la carte SD ainsi que l'écran LCD nous n'avons pas pu utiliser la carte Raspberry Pi 3 en pratique. Au lieu de cela nous avons cherché sur Internet l'écran nécessaire pour la console c'est-à-dire celui qui ne prend pas tous les GPIO de la carte Raspberry (car les I/O seront utilisés pour les boutons poussoirs). 

Cinquième séance (07/02/18)
--
Lors de la séance nous avons demandé de commander l'écran LCD 3.5 pouces. On a eu la possibilté de tester la carte Raspberry avec l'écran (7 pouces) qu'on a eu temporairement et la carte SD qu'on nous a passé. Suite à des nombreux essaies nous avont été confronté à un problème. Il consistait dans le fait que l'écran ne s'allumait pas ce qui était necéssaire pour installer le système operationnel sur la carte Raspberry. De plus, après la séance on s'est rendu compte que le système operationnel que la carte SD contenait ne nous convient pas pour certaines raisons. 

Sixième séance (14/02/18)
--
Pour la séance nous avons préparé la carte SD avec le système operationnel Ubuntu. Directement nous avons téléchargé le logiciel Processing qui permettra de lire les jeux codés en Java. Cette fois-ci l'écran s'allume bien mais la résolution qui était trop grande par rapport à la taille de l'écran. Donc il était assez difficile de lire quelque chose directement sur l'écran de 3.5 pouces.  

Septième séance (21/03/18)
--
Lors de cette séance nous avons cherché le moyen de changer la résolution de l'écran. Pour cela il a fallu aller dans un fichier sur la carte SD et ajouter quelques lignes de code. Puis nous avons cherché comment inverser l'axe x de l'écran car quand on tape à droite de l'écran le curseur apparaît à gauche.  

Huitième séance (28/03/18)
--
Les problèmes ont été résolus en reinstallant le système opérationnel Ubuntu Mate pour commencer les réglages à nouveau. Dès maintenant l'écran tactile marche sans aucun problème. 

Neuvième séance (05/04/18)
--
Entre les deux séances on a eu un autre problème avec la carte Raspberry. Suite à quelques utilisations de la carte, la barre de menu en haut de l'écran disparaît ce qui empêche de faire certaines choses, tels que l'accès facile à Internet, réglages importants, ainsi que de lancer le terminal à partir duquel on doit lancer le programme Processing.

Dixième séance (10/04/18)
--
Après quelques recherches on a réussi à trouver le moyen de lancer le terminal sans passer par la barre de menu cachée en noir. En faisant le branchement d'un bouton poussoir, nous avons testé si le petit code-test du Processing est compatible avec la Raspberry et marche bien. Cela a été le cas. 

Onzième séance (04/05/18)
--
Comme l'absence de la barre de menu est très genânte pour, on a essayé pour la dernière fois résoudre ce problème mais en vain. Il n'y a pas beaucoup d'information sur Internet concernant les problèmes d'affichage et surtout celui qu'on a eu avec notre carte Raspberry. Finalement on a décidé de faire avec et de ne rien changer.

Douzième séance (14/05/18)
--
Nous avons commandé les boutons poussoirs qui seront utilisés dans la console portable. Les soudures (sur la platine d'essaie) pour connecter les boutons à la carte Raspberry ont été fait. De plus, on a modelisé en 3D la boîte de la console où par la suite sera caché tout le matériel utilisé ainsi que les fils.  
