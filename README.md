# Maze-Generation-and-Pathfinding-Project
This project explores maze generation and demonstrates various graph search algorithms (BFS, DFS, UCS) to find paths within a generated maze.

## Overview
This Jupyter Notebook project combines maze generation with classic pathfinding algorithms. It allows for the creation of customizable mazes and then applies Breadth-First Search (BFS), Depth-First Search (DFS), and Uniform Cost Search (UCS) to find a path from a specified start point to a goal point within the generated maze. The results, including the maze and the found path, are visualized using Matplotlib.

## Features
### 1. Maze Generation
- Optimized Maze Generation: Generates mazes of a specified size with a configurable wall probability.
- Start and Goal Points: Automatically sets a start point at (0,0) and a goal point at the bottom-right corner of the maze.

### 2. Pathfinding Algorithms
- Breadth-First Search (BFS): Implements BFS to find the shortest path in terms of the number of steps.
- Depth-First Search (DFS): Implements DFS to explore paths, which may not be the shortest.
- Uniform Cost Search (UCS): Implements UCS to find the path with the lowest cumulative cost (in this case, uniform step cost, so it finds shortest path in unweighted graphs like BFS).

### 3. Visualization
- Maze Plotting: Displays the generated maze using Matplotlib, clearly showing walls and open paths.
- Path Visualization: Overlays the found path on the maze, highlighting the trajectory from start to goal.
