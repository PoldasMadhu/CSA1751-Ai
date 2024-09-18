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

