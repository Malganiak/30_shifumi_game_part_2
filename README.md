# 30_shifumi_game_part_2


Deuxième partie : Jouons au ShiFuMi !

Introduction :

L'objectif de ce brief est d'étendre les fonctionnalités de notre application Web dédiée au ShiFuMi en introduisant la reconnaissance de gestes via la WebCam comme moyen d'interaction. Dans la première version, nous avons réalisé une application jouable avec un simple clic souris. Dans cette seconde itération, nous allons intégrer la reconnaissance de gestes à l'aide d'un algorithme de Computer Vision, permettant ainsi aux utilisateurs de choisir entre Pierre, Feuille ou Ciseaux en effectuant des gestes devant leur caméra.

Contexte du projet :

Le précédent brief nous a conduit à développer une application Web pour jouer au ShiFuMi en utilisant le clic souris comme mode d'interaction. Dans cette phase, nous souhaitons remplacer cette méthode par la reconnaissance de gestes à l'aide de la WebCam. En tant que Développeur.e en Intelligence Artificielle, votre mission consiste à concevoir un algorithme de Computer Vision capable de distinguer les gestes correspondant à Pierre, Feuille et Ciseaux.

Plan d'action :

Construction d'une base de données d'images de gestes Pierre, Feuille et Ciseaux (scraping, site Web, etc. - choisissez la source de données appropriée).
Entraînement d'une Intelligence Artificielle sur cette base de données, en envisageant notamment l'utilisation du Transfer Learning.
Intégration de la nouvelle fonctionnalité à l'application Web en utilisant des bibliothèques telles qu'OpenCV pour la reconnaissance visuelle.
Question subsidiaire :

Proposez un test de non-régression pour évaluer l'impact de l'ajout de cette nouvelle fonctionnalité à votre application.

Livrables :

Fourniture des scripts (en Python et autres langages) contenant le code nécessaire pour l'application étendue.

Critères de performance :

Assurez-vous que l'exactitude sur le jeu de test soit strictement supérieure à 95%.
