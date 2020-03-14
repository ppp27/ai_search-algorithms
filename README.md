# ai_search-algorithms
To solve the 8-puzzle problem

Here the algorithm taught in the class has been implemented to solve the 8-puzzle problem using the A* search algorithm

*the state of the node
-node.state
*the row and column of the 8-puzzle problem grid
-row
-col
*for the directions we use
-L->left direction
-R->right direction
-U->upward direction
-D->downward direction
*cost and path for updating the cost values and path for finding the optimal path.

here the path cost is calculated starting from the start node untill the goal node is reached.
The heuristic value,ie the path cost keeps on updating when new nodes are being visited .
The path with the least value of the path cost is our optimal solution.
