## A Simple A* Pathfinding App

---
### Tech Stack Used

- Python 3.9
- PyGame 2.1.2

---
### Overview

The A* pathfinding algorithm is an informed search algorithm that ignores unnecessary searches by using weighted graphs.

*Formula:*

F(n) = G(n) + H(n)

F : Estimate of the distance from start to end nodes (sum of G(n) and H(n))
H : Estimate of the distance from node 'n' to the end node
G : Current shortest distance to get from the start node to node 'n'