# Connect 4 with Alpha-Beta Pruning
Connect Four is a classic two player board game where the objective is to be the first player to connect four of your own colored discs in a row, either horizontally, vertically, or diagonally, on a grid of 6x7. You will go against an advanced AI that uses the alpha-beta pruning algorithm.

## Files:

**main.py**: main Python script that contains the game logic, GUI, and alpha-beta algorithm implementation

## Layout of Code:
1. **Constants and Initialization**:
   - Definitions of colors, board dimensions, player pieces, and window length for winning sequences.
   - Initialization of Pygame and game variables.

2. **Board Setup and Utility Functions**:
   - Functions for creating the game board, dropping pieces, checking for valid moves, and retrieving the next open row.
   - Additional functions for printing the board, checking for winning moves, and evaluating game states.

3. **AI Algorithms**:
   - Implementation of the alpha-beta pruning algorithm for the AI opponent.
   - Functions for scoring positions, evaluating windows, and determining terminal nodes.

4. **Game Loop and Event Handling**:
   - Main game loop handling user input events (mouse clicks) and managing game state transitions.
   - Includes logic for player moves, AI moves, and game over conditions.

## How to Run:
1. Clone the Repository
2. run a virtual environment
2. run ``pip install -r requirements.txt`` into terminal
3. run ``python main.py`` into terminal or run the game on your IDE
