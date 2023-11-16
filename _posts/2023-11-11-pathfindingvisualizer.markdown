---
layout: posts
title:  "Pathfinding Visualizer"
date:   2023-11-11 18:59:00 +0000
categories: work
highlight_home: true
tags: C++, SFML
header:
 overlay_image: "/assets/images/pathfinding/overlay.png"
 teaser: "/assets/images/pathfinding/overlay.png"
 caption: "Sample Output"
---
Visualization of popular pathfinding algorithms

### Introduction:
In computer science and game development, pathfinding algorithms play a pivotal role in shortest or optimal paths to get from one point to another. In this project, I explore and visualize the working of pathfinding algorithms - specifically, Breadth-First Search (BFS), Dijkstra's and A*.

### Technology Used
I developed this project in Visual Studio using C++ and SFML (Simple and Fast Multimedia Library), a graphics library that facilitates the creation of interactive applications. 

### Algorithms
The algorithms implemented in this project are -

1. Breadth-First Search (BFS): A fundamental        
   algorithm in graph theory, explores all the vertices at the current depth before movig on to the next depth level.

2. Dijkstra's Algorithm: An informed algorithm, 
   makes decisions based on the accumulated cost to reach each node and finds the path with the minimum total cost.

3. A* Algorithm: Introduces heuristics to improve 
   efficiency. It aims to find the shortest path but uses an estimation of the remaining distance from the current node to the goal.

### Working
The code creates a grid and randomly assigns some of the cells as walls to create obstacles for the pathfinding algorithms. The Generate Map button can be used to genenate new random walls. 

We can then select the algorithm to run and view the cells that the algorithm visited as well as the path it chose to reach the end point. The total length of the paths i.e. the number of cells a path is made up of and the times taken by the algorithms are outputted.

<video width="640" height="480" controls loop>
  <source src="/assets/images/pathfinding/sample_video.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

### Conclusion