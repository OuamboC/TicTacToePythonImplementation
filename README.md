
# TicTacToePythonImplementation

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Procedural Paradigm Explanation](#procedural-paradigm-explanation)
- [Contact](#contact)

## Introduction
Welcome to the TicTacToePythonImplementation project! This project is a simple graphical Tic-Tac-Toe game built using Python and the `tkinter` library for the graphical user interface.

## Features
- **User-Friendly Interface**: Easy-to-use graphical interface with buttons for each tile and a restart button.
- **Two-Player Game**: Players take turns to place their tokens (X and O) on the board.
- **Win Detection**: Automatically checks for a winner or a tie after each move.
- **Reset Functionality**: Allows the game to be restarted at any point.

## Prerequisites
- Python 3.6 or higher.

## Installation
1. **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/TicTacToePythonImplementation.git
    cd TicTacToePythonImplementation
    ```

2. **Install the required packages** (if any, such as `tkinter` for Linux users):
    ```sh
    sudo apt-get install python3-tk
    ```

## Usage
1. **Run the game:**
    ```sh
    python tictactoe.py
    ```

2. **Gameplay:**
   - Click on any tile to place your mark.
   - The label at the top shows whose turn it is.
   - The game checks for a winner or tie after each move.
   - Click the "Restart" button to start a new game.

## Project Structure
- **Main Functions:**
  - `set_tile(row, column)`: Handles the placement of a player's mark on the board.
  - `check_winner()`: Checks for winning conditions or a tie.
  - `new_game()`: Resets the game to its initial state.

- **Colors:**
  - **Player X**: Blue (`#4584b6`)
  - **Player O**: Yellow (`#ffde57`)
  - **Board Background**: Gray (`#343434`)
  - **Winning Tiles Background**: Light Gray (`#646464`)

## Procedural Paradigm Explanation
This project showcases the **procedural programming paradigm** through its structured approach:
- **Functions**: Each major task in the game is handled by a dedicated function, making the code modular and easy to understand.
- **State Management**: Global variables (`curr_player`, `turns`, `game_over`, `board`) manage the state of the game, ensuring that each function can update and access the current state as needed.
- **Event Handling**: User interactions (like clicking a tile) are handled by binding events to functions, making the code responsive and interactive.

## Contact
If you have any questions or feedback, feel free to reach out to me at ouambocanis@gmail.com.
