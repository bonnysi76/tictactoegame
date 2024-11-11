## Tic Tac Toe Game - README

This project is a simple Tic Tac Toe game built with HTML, CSS, and JavaScript.

### Features
1. **Game Board**: A 3x3 grid of input fields represents the game board, where each cell is clickable.
2. **Turn Display**: Shows whose turn it is, alternating between "X" and "O."
3. **Win Detection**: Checks for winning rows, columns, or diagonals after each move. Highlights winning cells if a player wins.
4. **Tie Detection**: If all cells are filled with no winner, the game ends in a tie.
5. **Reset Button**: Clears the board, resetting the game to start fresh.

### Files
- **index.html**: Contains the HTML structure for the Tic Tac Toe grid and UI elements.
- **tic.css**: Styles the grid layout, making each cell appear as a square, and adds styles for headers and buttons.
- **tic.js**: Includes the game logic, managing player turns, win conditions, and the reset functionality.

### Code Breakdown
- **Functions (myfunc_3 to myfunc_11)**: Handle each cell’s behavior when clicked, placing an "X" or "O" based on the turn, then disabling the cell.
- **Player Toggle (flag variable)**: Alternates between Player X and Player O with each turn.
- **Win Checking (myfunc)**: Checks for a winner after each turn. If a win is detected, the winning cells are highlighted and a message is displayed. If the board is full and there’s no winner, the game declares a tie.
- **Reset Function (myfunc_2)**: Refreshes the game by reloading the page, clearing the board, and resetting the game state.

### How to Start
1. Write the following code in separate files:
   - **index.html** for structure
   - **tic.css** for styling
   - **tic.js** for game logic
