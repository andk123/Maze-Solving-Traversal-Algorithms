# Maze-Solving-Traversal-Algorithms

Here is the experimental results of comparing different searching algorithm using the maze runner. In the following order, we have Breadth-First Search, Depth-First Search, and A* Search.

The three algorithms used are Breadth-First Search, Depth-First Search and A* Search.

## Breadth-First Search

BFS is a search algorithm for traversing a graph or tree. It starts by visiting a node, then adds all of that node’s neighbors into the queue. Each time it adds a neighbor to the queue, it adds a pointer that references the neighboring node’s parent. Once the queue is empty, which means all nodes have been visited, or the goal node is found (for early-exit implementations), the pointers are traced from the goal back to the source.

## Depth-First Search

DFS is a search algorithm for traversing a graph or tree. Rather than considering its shallow neighbors first like BFS, it plunges all the way to the bottom of a given branch before considering the next neighbor. Once the stack is empty, which means all nodes have been visited, or the goal node is found (for early-exit implementations), the pointers are traced from the goal back to the source.

## A* Search

Unlike BFS and DFS, A* is an informed search algorithm. A* is implemented by searching the possible paths to the goal and opting for the one that incurs the smallest cost. The cost used by A* is the actual distance incremented from the start to the current node plus the estimated distance to the goal. To determine the cost to the goal, there are a number of heuristics. Two popular options are Manhattan distance and straight-line distance. In the Manhattan heuristic, the distance to the goal in the vertical direction plus the distance to the goal in the horizontal direction. While in the straight-line heuristic, the straight-line distance to the goal is used as the estimate.