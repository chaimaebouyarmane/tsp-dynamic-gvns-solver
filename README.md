# Traveling Salesman Problem Solver with Dynamic Programming and GVNS :penguin:
[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://boutainaelyaziji-tsp-project-app-cod2bj.streamlit.app/)

The objective of this project is to solve the Traveling Salesman Problem (TSP), a mathematical problem that involves finding the shortest path to connect a set of cities with given distances while visiting each city exactly once and returning to the starting city. We have implemented several methods to solve this problem, including an exact method using dynamic programming and a metaheuristic method known as GVNS.

### Demo  __click on the link below__ : :100:

<div align="center">

<a href="https://boutainaelyaziji-tsp-project-app-cod2bj.streamlit.app/">
<img src="https://github.com/BoutainaELYAZIJI/TSP_project/blob/main/imgs/HomePage.png">
<p>Click here to see the demo</p>
</a>

</div>

### Description : :sunglasses:
This project provides a user interface for selecting an approach from the sidebar to perform tasks related to the Traveling Salesman Problem (TSP). To get started, the user needs to upload an Excel or CSV file. We recommend using the "TSP Maroc Data" dataset to test the approach.
Next, the user is required to enter the name of the sheet in the uploaded file and the name of the first city to initiate the computation. The approach then explores the minimum distance between different cities and generates the minimum path that the salesman should take to visit all the cities and return to the starting point.
The user can also generate a visualization graph to view the minimum path and the distance between cities. Once the visualization is generated, the user can download the graph for future reference. This approach can be helpful for businesses and organizations that require optimized route planning for efficient transportation and logistics.

- TSP Pseudocode :computer:

<img src="https://github.com/BoutainaELYAZIJI/TSP_project/blob/main/imgs/pseudo_code.png">

### :full_moon_with_face: Dynamic Programming Approach
<img src="https://github.com/BoutainaELYAZIJI/TSP_project/blob/main/imgs/DP.png">

### :new_moon_with_face: Metaheuristic Approach (GVNS)
<img src="https://github.com/BoutainaELYAZIJI/TSP_project/blob/main/imgs/GVNS.png">

 ### :balloon: Successfully Generated Graph
 You can download the graph using the button below :) 
 
 <img src="https://github.com/BoutainaELYAZIJI/TSP_project/blob/main/imgs/Graph_succes.png">
 
### Mobile View :vibration_mode:
<img src="https://github.com/BoutainaELYAZIJI/TSP_project/blob/main/imgs/mobile.png">

### Installation :arrow_down:

```shell script
pip install streamlit
pip install pandas 
pip install streamlit_option_menu
pip install matplotlib
pip install numpy
pip install streamlit-lottie
