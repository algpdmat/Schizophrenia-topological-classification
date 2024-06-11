# Topological Classification in Schizophrenia

## Overview

This repository contains Python scripts for performing topological classification in schizophrenia. The work and results are discussed in detail in the article by André Luiz de Góes Pacheco, a postdoctoral researcher at iLIKA-UFRPE.

### Article Reference
Pacheco, A. L. G. (2024). Topological classification in schizophrenia. *Brazilian Journal of Health Review*. Available at: [https://ojs.brazilianjournals.com.br/ojs/index.php/BJHR/article/view/68803](https://ojs.brazilianjournals.com.br/ojs/index.php/BJHR/article/view/68803)

## Prerequisites

To use the scripts in this repository, you need to have Python installed along with the following packages:

- `networkx`: A package for the creation, manipulation, and study of the structure, dynamics, and functions of complex networks.
- `numpy`: A fundamental package for scientific computing with Python.
- `matplotlib`: A comprehensive library for creating static, animated, and interactive visualizations in Python.

You can install these packages using pip:

```bash
pip install networkx numpy matplotlib


Scripts
1. Graph Metrics Calculation and Classification
File: classification.py

Description:
This script calculates various centrality metrics for a given graph and classifies the graph into predefined groups based on these metrics. It includes functions for calculating the mean degree, betweenness, eigenvector, and closeness centralities, and then compares these values with known groups to identify the most likely classification.

Functions:

calculate_graph_metrics(graph): Computes centrality metrics for a graph.
classify_group(graph): Classifies a graph into one of the predefined groups.
2. Curvature Calculation and Centrality Visualization
File: visualization.py

Description:
This script calculates the Forman-Ricci curvature for each edge in a graph and visualizes the graph with curvature-based coloring. It also highlights the top 10 nodes by different centralities, using mixed colors for nodes that are top-ranked in multiple centralities.

Functions:

calculate_and_visualize_forman_ricci_curvature(G): Computes Forman-Ricci curvature and visualizes it on the graph.
calculate_and_visualize_top10_centralities(G): Highlights top nodes based on centralities and visualizes the graph.

Pacheco, A. L. G. (2024). Topological classification in schizophrenia. Brazilian Journal of Health Review. Available at: https://ojs.brazilianjournals.com.br/ojs/index.php/BJHR/article/view/68803
