# Graph-Algorithms-Visualizer-Prim-s-and-Kruskal-s-MST

This project is a web-based tool to visualize and understand two fundamental graph algorithms: **Prim's Algorithm** and **Kruskal's Algorithm**. It allows users to interactively create graphs, add nodes and edges, and visualize the step-by-step execution of these algorithms to find the Minimum Spanning Tree (MST).

## Features

- **Interactive Graph Creation**: Add nodes and edges to create your own graph.
- **Weighted Edges**: Assign weights to edges to simulate real-world scenarios.
- **Prim's Algorithm**: Visualize the step-by-step process of Prim's Algorithm to find the MST.
- **Kruskal's Algorithm**: Visualize the step-by-step process of Kruskal's Algorithm to find the MST.
- **Clear Board**: Reset the graph and start fresh.
- **Responsive Design**: Works on both desktop and mobile devices.

## How to Use

1. **Adding Nodes**: Click anywhere on the graph area to add a node.
2. **Adding Edges**: 
   - Click on a node to select it.
   - Click on another node to create an edge between them.
   - Enter the weight of the edge when prompted.
3. **Running Algorithms**:
   - Click the "Solve" button to visualize the selected algorithm (Prim's or Kruskal's).
   - The solution graph will be displayed below the original graph.
4. **Clearing the Board**: Click the "Clear Board" button to reset the graph.

## Algorithms Overview

### Prim's Algorithm
Prim's Algorithm is a greedy algorithm that finds a minimum spanning tree for a weighted undirected graph. It starts with an arbitrary node and grows the MST one edge at a time, always adding the cheapest possible connection from the tree to another vertex.

### Kruskal's Algorithm
Kruskal's Algorithm is another greedy algorithm used to find the minimum spanning tree. It sorts all the edges in the graph in increasing order of weight and adds them to the MST one by one, ensuring that adding the edge does not form a cycle.

## Technologies Used

- **HTML5**: Structure of the web pages.
- **CSS3**: Styling and layout.
- **JavaScript**: Logic and interactivity.
- **SVG**: Rendering lines and edges.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Manav2905/Graph-Algorithms-Visualizer-Prim's-and-Kruskal's-MST.git

2. Navigate to the project directory:
   ```bash
   cd graph-algorithms-visualizer

3. Open "dashboard.html" in your browser to start using the application.
