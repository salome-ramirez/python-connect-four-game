# python-connect-four-game

🔴 Connect Four: The Ultimate Python Challenge! 🟡

🚀 Overview

Welcome to the classic game of Connect Four, built right in a Python Jupyter Notebook! Get ready to face off against a friend in this simple, text-based version of the $6 \times 7$ grid challenge.

The goal is simple: be the first player to line up four of your tokens in a row—either horizontally, vertically, or diagonally.

Player

Token

Player 1

x

Player 2

o

🛠️ How to Play

Requirements

You only need a standard Python environment that can run a Jupyter Notebook (.ipynb) file.

Starting the Game

Open and run the code cells in the Connect4_Final (2).ipynb file.

The game will automatically start by calling the play_game() function.

Gameplay

The game board will print to the console. The bottom row of numbers (1 2 3 4 5 6 7) indicates the columns where you can drop your token.

When prompted, Player x will start first. Enter the column number (1-7) where you want to drop your piece.

The board will update, and the turn will switch.

Win! 🎉 If you connect four, the winning tokens will be capitalized on the board (e.g., X or O) and the game will end.

Draw! 🤝 If the board fills up with no winner, the game is declared a draw.

You'll be asked if you want to Play again? y/n after every game!

🧩 Code Deep Dive

The game logic is contained within the Connect4_Final (2).ipynb. Here's a quick look at the main functions that make the game work:

Function

What it Does

new_gameboard()

Creates the empty $6 \times 7$ grid, represented by periods (.).

showboard()

Displays the current board state and the column numbers.

drop(token, colnum, gameboard)

Finds the lowest available slot in the selected column and places the player's token.

four_in_a_row()

The heart of the game! Checks for 4-in-a-row in all directions (horizontal, vertical, and both diagonals).

draw()

Checks if the entire board is full.

play_game()

Manages the main game loop, player inputs, error handling, and end-of-game logic.

Created by Salome Collante-Ramirez (Spring 2025)
