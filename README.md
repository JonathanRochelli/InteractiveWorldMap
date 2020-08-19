# Carte du monde interactive
## Fonctionnalités

La carte dispose d'un système de **zoom** permettant d'améliorer la lisibilité.
Il est aussi possible, lors du clique sur un pays, d'avoir les **détails** de celui-ci.
Les informations de chaque pays sont récoltées via des requêtes à l'API **REST Countries v1**.
Pour avoir les détails de cette API, veuillez vous rendre sur cette [page](https://rapidapi.com/apilayernet/api/rest-countries-v1)

## Utilisation de l'API

Pour utiliser l'API gratuite **REST Countries v1**, il est nécessaire d'avoir une clé d'API. Vous pouvez vous en procurer une sur le site de [RapidAPI](https://rapidapi.com/). Il suffit pour cela de vous inscrire gratuitement sur le site et de chercher l'API **REST Countries v1**. Ensuite, dans la section **Header Parameters** de l'onglet **Endpoints** vous trouverez un champ nommé **X-RapidAPI-Key**. La valeur associée à ce champ est votre clé d'API. Pour terminer, il vous faudra copier/coller cette clé dans la variable apiKey qui se situe dans la fonction **getInfoByName()** présente dans le code Javascript (js/script.js).

## Architecture du code

Le code de ce répertoire est découpé en 3 parties :
- Le dossier js/ contenant le code Javascript
- Le dossier css/ contenant les styles de la page
- Le fichier `interactiveWorldMap.html` contenant le code la page

## Lien vers la démonstration : [Démo](https://jonathanrochelli.github.io/interactiveWorldMap/interactiveWorldMap.html)


