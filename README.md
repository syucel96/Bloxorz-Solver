# Bloxorz-Solver
offers 2 different search algorithms to find an optimal path to the goal state for the game Bloxorz

You can find the Bloxorz game at https://www.mathplayground.com/logic_bloxorz.html

The initial state of the board has to be hardcoded into the code. You shouldn't encounter any problems even if you change the size of the matrix.
The first algorithm performs a Uniform Cost Search Algorithm and the second one performs an A* Search Algorithm.

The algorithms return a goal reached message, the path length, the path, the number of visited nodes, visited nodes and the maximum size the priority queue reached during the execution.
The number of visited nodes can be seen as the time complexity and the max size of the heap can be seen as space complexity.
