# Kontrol2

Widget d'action personnalisable de type "Curseur-Slider" pour Jeedom.

Le curseur s'anime aussi bien par un clic, un glissement avec prévisualisation ou un scroll de souris.

<img src="/doc/Kontrol2.gif" alt="gif présentation"/>

De nombreux paramètres de personnalisation sont disponibles via l'ajout de paramètres optionnels sur le widget.
>**Important**: il est impératif de bien respecter la casse (majuscules/minuscules)

#### Les couleurs de chaque éléments sont personnalisables individuellement:
* **colEtat**: Choisir la couleur de la valeur en retour d'état au centre. *(Blanc par défaut - #FFFFFF)*
* **colUnite**: Choisir la couleur de l'unité. *(Blanc par défaut - #FFFFFF)*
* **colFond**: Choisir la couleur de fond de la jauge. *(Couleur catégorie commande par défaut - #cmdColor#)*
* **colCurseur**: Choisir la couleur du curseur. *(Blanc par défaut - #FFFFFF)*

Les couleurs peuvent être renseignées par [leur valeur hexadécimale ou leur nom HTML](https://en.wikipedia.org/wiki/Web_colors#X11_color_names).  

>**Attention**: Afin d'afficher la prévisualisation lors du glissement, la couleur du paramètre '**colCurseur**' doit impérativement être stipulée à l'aide de son code hexadécimal.

>**Astuce**: Pour appliquer la couleur de la catégorie il faut saisir le tag: #cmdColor#.

#### Possibilité de modifier la forme et la taille du widget:
* **taille**: Paramétrage de la taille du widget en pixels. *(110px\*110px par défaut)*
* **epaisseur**: Paramétrage de l'épaisseur du curseur de 0 à 1. *(0.4 par défaut)*
* **curseur**: Possibilité de sélectionner une taille de curseur en pixels au lieu d'un remplissage. *(exemple: 30)*
* **angleDepart**: Permet de choisir le point de départ du curseur de 180 à -180. *(-165 par défaut)*
* **angleArc**: Permet de choisir le degré d'ouverture de la jauge de 0 à 360. *(330 par défaut)*
>**Attention**: concernant le paramètre **angleArc** les valeurs entre 346 et 359 empêche le clic dans la fin de la jauge.  
>De même un angle de 0 fera disparaïtre la jauge, seul le scroll de souris restera possible.

#### Cacher la valeur d'état et/ou l'unité:
* **Etat**: Pour cacher la valeur de retour d'état au centre du widget. *('on' par défaut)*
* **Unite**: Pour cacher l'unité sous la valeur au centre du widget. *('on' par défaut)*

L'ensemble des paramètres optionnels est rappelé au début du code du widget.

---------------