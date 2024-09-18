8 QUEENS PROBLEM
For each successor node:
If it's in the closed list, skip it.
If it's not in the open list, add it and calculate its f-cost.
If it's already in the open list with a higher f-cost, skip it.
STEP 6:If the open list is empty and the goal node is not reached, no path exists.


map colouring.
ALGORITHM:
STEP1:Initialize: Create a list of regions and their corresponding neighbors. Initialize a dictionary to store the assigned colors for each region.
STEP 2:Select Region: Choose a region that hasn't been colored yet.
STEP 3:Check Constraints: Check the colors assigned to neighboring regions. Make sure the chosen color doesn't conflict with the colors of its neighbors.
STEP 4:Assign Color: If a valid color is found, assign it to the selected region in the dictionary.
STEP 5:Recursion: Recursively move to the next uncolored region and repeat steps 2-4.
STEP 6:Backtrack: If you reach a point where no valid color can be assigned, backtrack to the previous region and try a different color.
STEP 7:Solution: If all regions are colored successfully without conflicts, you have found a solution

Tic Tac Toe game.
ALGORITHM:
STEP 1: Initialize the game board (3x3 grid) with empty spaces.
STEP 2:Create a loop to alternate between players' turns until the game ends.
STEP 3:Display the current game board.
STEP 4:Prompt the current player for their move (row and column).
STEP 5:Check if the selected cell is empty. If not, ask the player to choose again.
STEP 6:Update the selected cell with the player's symbol (X or O).
STEP 7:Check for a win condition: 3 symbols in a row, column, or diagonal.
STEP 8:If a win is detected, declare the current player as the winner.


Apha & Beta pruning algorithm .
ALGORITHM:
STEP1:Start with the initial game state.
STEP2:For each level of the game tree, use the Alpha-Beta Pruning algorithm to determine the STEP3: best move by considering the possible actions and their associated values.
STEP4:Initialize alpha as negative infinity and beta as positive infinity.
STEP5:Perform a recursive search through the game tree, alternating between maximizing and minimizing players.
STEP6:During the search, update the alpha value for the maximizing player and the beta value for the minimizing player.
STEP7:If the beta value becomes less than or equal to the alpha value at any point, prune the rest of the sub-tree, as the opponent will never allow the game to reach this state.
STEP8:Continue the search until the entire game tree is explored or until a terminal state is reached.
STEP9:Return the best move found during the search.


Decision Tree.
ALGORITHM:
STEP1:start the program.
STEP2: To divide the data based on target variables, choose the best feature employing Attribute   Selection Measures (ASM).
STEP3:Then it will divide the dataset into smaller sub-datasets and designate that feature as a decision node for that branch.
STEP4:Once one of the conditions matches, the procedure is repeated recursively for every child node to begin creating the tree.
STEP5:The identical property value applies to each of the tuples.
o	There aren't any more qualities left.
o	There aren't any more occurrences.

Feed forward neural Network.
ALGORITHM:
STEP1:start the program 
STEP2:The input layer comprises neurons that receive input.
STEP3:The hidden layer contains a large number of neurons that modify the inputs and interact with the output layer.
STEP4:The output layer contains the result of the computation.

Missionaries Cannibal problem. ALGORITHM: STEP1: One way to solve the Missionaries and Cannibals problem is to use a variation of the Breadth-First Search (BFS) algorithm. STEP2:The idea is to represent the states of the problem (the number of missionaries and cannibals on each side of the river and the boat's location) as nodes in a graph. STEP3:Then, by systematically exploring the graph using BFS, you can find a valid sequence of moves that solves the problem.

Vacuum Cleaner problem. ALGORITHM: STEP1: Initialize: Start at a given position on the grid. STEP 2:Check and Clean: If the current cell is dirty, clean it. STEP 3:Move Decision: Choose the next cell to move to. Options include: Move to the nearest dirty cell. STEP 4:Move in a specific pattern (e.g., zig-zag) to ensure coverage. STEP 5:Use a combination of both strategies for optimal cleaning. STEP 6:Move: Move the vacuum cleaner to the chosen cell. STEP 7:Repeat: Go back to step 2 until all cells are clean.

8 puzzle problem ALGORITHM: STEP1:State Representation: Represent the puzzle as a 3x3 grid, where each cell contains a number (1-8) or is empty (0). STEP2: Node Representation: Each node in the search tree represents a state of the puzzle. It contains the current state, the previous state (parent), the move that led to this state, and the cost (usually the sum of the path cost and a heuristic estimate). STEP 3:Heuristic Function: Choose a heuristic function that estimates the cost from the current state to the goal state. A common heuristic for the 8-puzzle is the Manhattan distance, which is the sum of the horizontal and vertical distances of each tile to its correct position. STEP4: Priority Queue: Use a priority queue (e.g., a min-heap) to store nodes during the search. Nodes are dequeued based on their total cost (p222ath cost + heuristic cost). STEP5: A Algorithm*: a. Initialize the priority queue with the initial state. b. While the priority queue is not empty: i. Dequeue the node with the lowest total cost. ii. If the current state is the goal state, the solution is found. iii. Generate successor states by moving the empty space in all possible directions (up, down, left, right). iv. For each successor state: - Calculate the cost (path cost + heuristic cost). STEP 6:Solution Extraction: Once the goal state is reached, follow the parent pointers from the goal node to the initial node to extract the sequence of moves that lead to the solution.

