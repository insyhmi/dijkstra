# Dijkstra Algorithm Simulation

A website to simulate Dijkstra's algorithm using pure javascript and Cytoscape.js

This project demonstrates the algorithmic method of Dijkstra in finding the shortest distance to reach the vertices from a starting point.

Involving non-negative vertices, the algorithm greedily compares edges and find the most optimal route to reach a particular point in the graph.

## Usage

To add a node/vertex, click "Add Vertex" and enter necessary information. The vertex ID's should be unique to other vertices.

To add an edge, click "Add Edge", and enter necessary information. The vertices involved should exists in the environment.

To run, click "Run Simulation" and watch the algorithm finds the shortest path for each vertex in action. 

To check preferred path, click on a row in the result table. It will highlight the path from the source vertex to the target vertex.

To fit the graph in view, click "Fit View".

To clear the environment, click "Reset Graph".
## 03.03.2026

still work in progress

## 03.05.2026

the logic has been implemented (I just rewrote from my script in gists in JS. [See here](https://gist.github.com/insyhmi/85fadf3032bce35a51b5f9337ba1086f))

## 03.08.2026

- working functional buttons
- implemented result table
- clicking on a row within the table shows the shortest path to take from the starting point to target
- slight color changes

## 03.11.2026

- animated color change properly demonstrate search algorithm
- confirmation box before resetting the graph
- fit graph to view button
- speed multiplier slider (not the best but hey its something)

## 03.14.2026

- validating the weight is a number
- deployment