# Application Web de résolution du Problème du Voyageur de Commerce avec Programmation Dynamique et GVNS :penguin:
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://boutainaelyaziji-tsp-project-app-cod2bj.streamlit.app/)

L'objectif de ce projet est de résoudre le problème du voyageur de commerce, un problème mathématique qui consiste à trouver le chemin le plus court pour relier un ensemble de villes données, en visitant chaque ville exactement une fois et en revenant à la ville de départ. Nous avons mis en place plusieurs méthodes pour résoudre ce problème :<br/> une méthode exacte représentée par la programmation dynamique ainsi qu'une autre méthode métaheuristique (GVNS).

### Démo  __cliquez sur le lien ci-dessous__ : :100:

<div align="center">

<a href="https://boutainaelyaziji-tsp-project-app-cod2bj.streamlit.app/">
<img src="https://github.com/BoutainaELYAZIJI/TSP_project/blob/main/imgs/HomePage.png">
<p>Cliquez ici pour voir la démo</p>
</a>

</div>

### Description : :sunglasses:
Ce projet offre une interface utilisateur pour sélectionner une approche à partir de la barre latérale afin d'effectuer une tâche liée au Problème du Voyageur de Commerce (TSP). Pour commencer, l'utilisateur doit télécharger un fichier Excel ou CSV. Le jeu de données "TSP Maroc Data" est recommandé pour tester l'approche.
Ensuite, l'utilisateur doit saisir le nom de la feuille dans le fichier téléchargé et le nom de la première ville pour démarrer le calcul. L'approche explore ensuite la distance minimale entre différentes villes et génère le chemin le plus court que le voyageur doit emprunter pour visiter toutes les villes et revenir au point de départ.
L'utilisateur peut également générer un graphique de visualisation pour voir le chemin minimal et la distance entre les villes. Une fois la visualisation générée, l'utilisateur peut télécharger le graphique pour référence future. Cette approche peut être utile pour les entreprises et les organisations qui nécessitent une planification optimisée des itinéraires pour une logistique et un transport efficaces.

- Pseudocode du TSP :computer:

<img src="https://github.com/BoutainaELYAZIJI/TSP_project/blob/main/imgs/pseudo_code.png">

### :full_moon_with_face: Approche Dynamique
<img src="https://github.com/BoutainaELYAZIJI/TSP_project/blob/main/imgs/DP.png">

### :new_moon_with_face: Approche Métaheuristique (GVNS)
<img src="https://github.com/BoutainaELYAZIJI/TSP_project/blob/main/imgs/GVNS.png">

 ### :balloon: Graphique généré avec succès
 Vous pouvez télécharger le graphique en utilisant le bouton ci-dessous :) 
 
 <img src="https://github.com/BoutainaELYAZIJI/TSP_project/blob/main/imgs/Graph_succes.png">
 
### Vue mobile :vibration_mode:
<img src="https://github.com/BoutainaELYAZIJI/TSP_project/blob/main/imgs/mobile.png">

### Installation :arrow_down:

```shell script
pip install streamlit
pip install pandas 
pip install streamlit_option_menu
pip install matplotlib
pip install numpy
pip install streamlit-lottie
