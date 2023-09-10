# TSP Solver: Dynamic Programming and GVNS Approaches 🌍

[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://boutainaelyaziji-tsp-project-app-cod2bj.streamlit.app/)

## Introduction

Welcome to the Traveling Salesman Problem (TSP) Solver, an interactive web application designed to find optimal solutions for the classic TSP using both Dynamic Programming and GVNS (General Variable Neighborhood Search) algorithms. The TSP is a fundamental combinatorial optimization problem that involves finding the shortest possible route that visits a given set of cities and returns to the origin city.

This project provides a user-friendly interface for solving TSP instances, visualizing solutions, and understanding the concepts behind these two powerful algorithms.

## Features

- **Dynamic Programming**: Utilizes dynamic programming to calculate the exact solution to small-to-medium-sized TSP instances.
- **GVNS Algorithm**: Implements the GVNS metaheuristic, a versatile local search method, to tackle larger TSP instances.
- **Interactive Visualization**: Visualizes the optimal TSP route on a map, making it easy to understand and interpret the results.
- **Upload Custom Data**: Allows users to upload their own datasets in CSV or Excel format for TSP problem-solving.
- **Performance Metrics**: Measures and displays performance metrics such as solution quality and computation time.
- **Download Solutions**: Provides the option to download the TSP solution as a CSV file for further analysis or integration into other applications.

## Demo

Explore the application and see it in action by clicking the link below:

[![Demo](https://github.com/BoutainaELYAZIJI/TSP_project/blob/main/imgs/HomePage.png)](https://boutainaelyaziji-tsp-project-app-cod2bj.streamlit.app/)

## Application Interfaces

### Dynamic Programming Interface

![Dynamic Programming Interface](https://github.com/BoutainaELYAZIJI/TSP_project/blob/main/imgs/DP.png)

### GVNS Algorithm Interface

![GVNS Algorithm Interface](https://github.com/BoutainaELYAZIJI/TSP_project/blob/main/imgs/GVNS.png)

### Interactive Visualization Interface

![Interactive Visualization Interface](https://github.com/BoutainaELYAZIJI/TSP_project/blob/main/imgs/Graph_succes.png)

## Getting Started

Follow these simple steps to run the TSP Solver locally:

### Prerequisites

Make sure you have Python and the following Python packages installed:

- `streamlit`
- `pandas`
- `matplotlib`
- `numpy`
- `streamlit-lottie`

You can install them using pip:

```shell
pip install streamlit pandas matplotlib numpy streamlit-lottie
