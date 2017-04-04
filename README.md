# 8 Puzzle Solver
c++ implementation for an 8 puzzle solver. The program allows the user to input an 8 puzzle problem and gives the user the
choice between 3 solving methods:
* Uniform Cost - The heuristics used for the next step to take is based on breadth first search. 
* A* Misplaced tiles - The heuristics is based on how many tiles are not on their proper spot. Priority is given to the move that 
the amount of tiles that are still misplaced
* A* Manhattan Distance - The heuristics is based on how many steps is needed in order to place all the tiles to their proper place.
Again, the least amount of steps needed to solve the puzzle is given priority.

