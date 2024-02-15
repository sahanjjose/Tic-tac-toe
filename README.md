# Tic-tac-toe
Implemented an AI to play Tic-Tac-Toe optimally, Using Minimax.

This project implements a Tic-Tac-Toe game with an AI opponent using the Minimax algorithm. The game consists of two main files:

runner.py: Contains the code to run the graphical interface for playing the game.
tictactoe.py: Contains all the logic for playing the game and for making optimal moves.

# Implementation Details

**Variables**
X, O, and EMPTY: Represent possible moves on the board.

# Functions to Implement

**player(board):**
Determines which player's turn it is.
Returns either X or O.

**actions(board):**
Returns a set of all possible actions that can be taken on a given board.
Each action is represented as a tuple (i, j) where i corresponds to the row and j corresponds to the cell in the row.

**result(board, action):**
Returns a new board state resulting from taking the given action.
Raises an exception if the action is not valid.

**winner(board):**
Determines the winner of the game, if there is one.
Returns X if X wins, O if O wins, or None if there is no winner.

**terminal(board):**
Determines if the game is over.
Returns True if the game is over, otherwise False.

**utility(board):**
Returns the utility of the board.
If X has won, returns 1. If O has won, returns -1. If it's a tie, returns 0.

**minimax(board):**
Returns the optimal move for the player to make on the given board using the Minimax algorithm.
Returns None if the board is a terminal board.

**How to Play**
Run python runner.py to play against the AI.
The AI is programmed to play optimally, so you can't beat it if both sides play optimally.

**Notes**
Tic-Tac-Toe is a tie given optimal play by both sides, so the AI is unbeatable if you also play optimally.
Enjoy playing against the AI and try to improve your skills!

# Acknowledgments
This project is part of a programming assignment or tutorial. It's based on the requirements provided by the instructor or documentation.
