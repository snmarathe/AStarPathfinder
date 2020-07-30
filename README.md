# A* Pathfinder
* This repo contains the code and visual for a pathfinder created using A* search algorithm. See pseudocode for A* algorithm [here](https://en.wikipedia.org/wiki/A*_search_algorithm#Pseudocode).
* See visual for the pathfinding process [here](https://snmarathe.github.io/AStarPathfinder/).
* A* search algorithm calculates a minimum-cost path between two nodes in a graph. It achieves this by minimizing the formula f(n) = g(n) + h(n) for every node 'n' it visits.
* In this formula, g is the distance (cost) from the starting node to node n, and h is the value of the heuristic function of n - an educated guess of the distance (cost) to reach the end node from node n.
