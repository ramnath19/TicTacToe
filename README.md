# TicTacToe

This is a simple web-based implementation of the classic game Tic-Tac-Toe using React.

**How to Play**

•	Click on the squares to make your move.
•	Try to get three in a row vertically, horizontally, or diagonally to win the game.
•	Reload the page to start a new game.

**Code Overview**

•	The game is built using React components: Board, Square, and Game.

•	The game logic checks for a winner after each move using a set of winning combinations.

•	Players take turns to make their move, and the winner is determined based on the board state.

Getting Started

To run the game locally:

•	Clone this repository.

•	Open the tictactoe.html file in a web browser.

**Code Explanations**

•	The resetButton allows you to reset the game by reloading the page.

•	The Board component manages the game state, player turns, and rendering the board.

•	The Square component represents each square on the board and handles user interaction.

•	The checkForWinner function checks for a winning combination in the game state.

•	The playCheeringSound function plays a cheering sound when a player wins.

•	The disableGameplayButtons function disables all buttons after a player wins.

**Roadmap for Future Improvements**

•	Add a scoreboard at the bottom that keeps track of how many games PlayerX and PlayerO have won.

•	Implement a "Reset Score" button for zeroing out each players' scores.

•	Add a confetti animation in the background for when a winner is declared.

•	Make the winning row of Xs or Os flash when the winner is declared.

