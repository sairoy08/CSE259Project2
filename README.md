# CSE259Project2
Members: Sudharshan Ramadass, Sai Roy

Sudharshan Ramadass:
- Worked on Task 1 to display the board and Task 3 for auto complete
- Created the print_board(Board) and print_rows(Board, Rank)
- Added to draw the horizontal lines between rows
- The print_row_cells function goes through each file in a row and determines what to print
- I coded cell_representation(Color, Type, Cell) to format how pieces appear
- Added piece_letter to convert piece types into single letters
- Modified the play(Board) loop so both playerA and playerB move automatically
- Tested the board display with different positions
- Verified the alternating turn system works and the game ends properly on checkmate or stalemate
- Added comments explaining how the board printing and auto-compete loop work

Sai Roy:
- I worked on Task 2 and built the repository
- The entire playerA implementation was done by copying and adapting the existing playerB code as instructed
- I created valueA(PieceType, Value) which assigns point values and strengthA to calculate position evaluation
- I added sufficientA for alpha-beta pruning
- Set ply_depthA(3) to control search depth playerA looks 3 moves ahead when deciding what to play
- I tested different depth values
- Made sure the evaluation function works by watching games and checking if playerA makes reasonable moves
- Added boundary checking to prevent overflow

Both of Us:
- Verified both players only make legal moves
- Tested edge cases together and debugged
- Ran multiple test games with different scenarios to catch bugs
- Made sure both players use their own evaluation functions like valueA for white and valueB for black
- Added comments to explain alpha-beta pruning and board recursion
