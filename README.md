# Last-Mile Delivery Analysis
Route Optimization and Behavioral Analysis of Last-Mile Deliveries using Amazon Challenge Data

This project explores route optimization and behavioral analysis of last-mile deliveries using graph theory, centrality metrics, and heuristics like the Traveling Salesman Problem (TSP). It combines interactive visualizations in Neo4j and Python to model a real-world delivery network.

## Project Overview

The objective is to analyze and optimize delivery routes by:

- Building a graph of delivery stops (nodes) and transitions (edges)
- Visualizing network structure using both **Neo4j** and **networkx**
- Identifying the most central delivery hubs using **degree centrality**
- Computing **shortest paths** between delivery points
- Solving the **Traveling Salesman Problem (TSP)** to suggest efficient cyclic delivery tours

## Tools & Libraries

- **Python** (JupyterLab)
- **Neo4j** – Graph database for interactive route modeling
- **NetworkX** – Graph analysis in Python
- **Matplotlib** – Static graph layouts
- **Pandas** – Data manipulation


## Key Features

- Graph loading and exploration using `nodes.csv` and `edges.csv`
- Neo4j import and visual validation of the delivery network
- Pathfinding using Dijkstra’s algorithm
- Top 10 central delivery stops analysis
- Route optimization using `greedy_tsp` approximation
- Visualizations in **Matplotlib** and **NetworkX**
