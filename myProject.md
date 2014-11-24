#ICOM - Cours HTML / CSS #

* Sarah MEILLOUR
* sarahmeillour@gmail.com

##Pourquoi mon projet est-il organisé de cette manière ?
###_(avantages et inconvénients de cette organisation)_

Le site est organisé de façon à être responsive, il s’adapte à l’écran de l’utilisateur permettant une meilleure expérience pour celui-ci. Notre contenu peut être personnalisé suivant l’appareil utilisé.


##Comment suis-je arrivé à ce résultat ?
###_(différentes étapes, problématique d'organisation)_

Tout d'abord on range ses fichiers par types:
les fichiers HTML à la racine du projet, un dossier pour les images, un dossier stylesheet pour les fichiers CSS.

Puis on analyse la structure de la maquette web: on identifie les différents blocs qui composent la page afin d’organiser le fichier HTML (header, slide, colonnes, footer). 
Après avoir mis en place tous les éléments dans le document HTML on fait la mise en page en CSS.

Pour le responsive design, on analyse la structure du site pour le découper en 12 colonnes de même largeur afin de prévoir l’agencement de nos colonnes pour les différentes tailles d’écran. On ajoute une balise meta viewport pour définir la surface du navigateur. On créait un fichier media queries en CSS qui va permettre de définir les points d’arrêt. On définit nos tailles pour chaque écran (PC, tablette et mobile) et on concatène les classes sur le dossier HTML pour les différentes dimensions.


---
##Quelle sont les difficultés rencontrées durant ces 6 sessions ?

Les difficultés rencontrées sont surtout liées à l'organisation des éléments afin qu'ils se comportent de façons différentes suivant la taille de l'écran utilisé (logique d'attribution des classes pour les différentes dimensions).