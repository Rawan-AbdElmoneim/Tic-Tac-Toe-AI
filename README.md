# Tic Tac Toe with AI

This Python program implements the classic game of Tic Tac Toe with an option to play against an AI opponent using the minimax algorithm. The game is built using the Pygame library for graphical representation and user interaction.

## Features

### Game Modes:
- **Player vs Player (PvP)**: Play against another human on the same computer.
- **Player vs AI (PvAI)**: Challenge an AI opponent that uses the minimax algorithm to make strategic moves.

### Difficulty Levels:
The AI has two difficulty levels:
- **Level 0 (Random AI)**: The AI makes random moves.
- **Level 1 (Minimax AI)**: The AI uses the minimax algorithm to play optimally.

### Visual Feedback:
The game interface provides visual feedback for:
- Marking squares with crosses (Player 1) or circles (Player 2).
- Drawing lines to indicate winning combinations.
- Highlighting the grid and lines in different colors.

## Screenshots
- **AI Victory**

 
  - ![Screenshot 2024-06-24 232744](https://github.com/Rawan-AbdElmoneim/Tic-Tac-Toe-AI/assets/142115846/0bc27440-b021-442e-ab96-13b56b9eb434)
 
    

- **Draw Game**

  
 -  ![Screenshot 2024-06-24 232852](https://github.com/Rawan-AbdElmoneim/Tic-Tac-Toe-AI/assets/142115846/4919b1de-4a99-4d5f-82a1-0c92edb082d8)


## Installation and Setup

### Requirements:
- Python 3.x
- Pygame library (`pip install pygame`)

### Running the Game:
1. Clone this repository or download the `tic_tac_toe_ai.py` file.
2. Navigate to the directory containing the file and run `python tic_tac_toe_ai.py`.

### Game Controls:
- **Switch Game Mode**: Press `G` to toggle between PvP and PvAI modes.
- **Restart Game**: Press `R` to reset the game.
- **AI Difficulty**:
  - Press `0` for Random AI.
  - Press `1` for Minimax AI.

### Gameplay:
- In PvP mode, players take turns clicking on the grid to place their mark.
- In PvAI mode, the human player competes against the AI. The AI evaluates the board using the minimax algorithm to make its move.

### Exiting the Game:
- Click the close button on the game window or press `Esc` to exit the game.

## Implementation Details

### Board Representation:
- The game board is represented as a 3x3 NumPy array (`self.squares`) where `0` indicates an empty square, `1` represents Player 1's mark (cross), and `2` represents Player 2's mark (circle).

### AI Implementation:
- The AI uses the minimax algorithm to recursively evaluate possible future game states and choose the optimal move based on the current game board.

### Graphics and User Interface:
- Pygame is used to create a graphical user interface (GUI) for the game, including drawing the board grid, marks, and lines indicating winning combinations.
