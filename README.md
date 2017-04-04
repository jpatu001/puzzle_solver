# 8 Puzzle Solver
c++ implementation for an 8 puzzle solver. The program allows the user to input an 8 puzzle problem and gives the user the
choice between 3 solving methods:
* Uniform Cost - The heuristics used for the next step to take is based on breadth first search. 
* A* Misplaced tiles - The heuristics is based on how many tiles are not on their proper spot. Priority is given to the move that 
the amount of tiles that are still misplaced.
* A* Manhattan Distance - The heuristics is based on how many steps is needed in order to place all the tiles to their proper place.
Again, the least amount of steps needed to solve the puzzle is given priority.

Once the program finished solving the puzzle, it will print a trace for the solution. The number of nodes expanded, Maximum Queue Size, and the Maximum Depth will also be printed out. 

# How to Run
* run make
* ./driver
* Enter the puzzle, with '0' being the empty space.
* Choose between Uniform Cost, A* Misplaced Tiles/ Manhattan Distance.

# Note
Uniform Cost can take a long time to finish when solving complex puzzles since every node is expanded in BFS manner.
By using Misplaced tiles/ Manhattan Distance for heuristics significantly improves the solving time by minimizing the amount of nodes to 
be expanded. 
