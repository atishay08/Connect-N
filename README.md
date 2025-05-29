# 🎮 Connect-N Game

Connect-N is a customizable two-player game inspired by Connect Four. Players take turns dropping colored pieces into a grid. The first player to connect **N** pieces in a row (horizontally, vertically, or diagonally) wins the game.

You can choose to play in:
- Player vs Player (PvP)
- Player vs Computer (PvC) with 3 difficulty levels (Easy, Medium, Hard)

## 🧠 Features

- Dynamic board size: choose any number of rows and columns.
- Customizable win condition: choose any value of N (3 or more).
- PvP and PvC modes.
- AI opponent powered by the Minimax algorithm with alpha-beta pruning.
- Visuals using Pygame with player names and winning highlights.
- Colorful GUI with real-time updates and animations.

## 💻 Technologies Used

- **Python 3**
- **Pygame** – for GUI rendering and event handling.
- **NumPy** – for efficient matrix operations and board representation.
- **Minimax Algorithm** – with alpha-beta pruning for AI difficulty.

## 🚀 Getting Started

### Prerequisites

Ensure you have Python installed (preferably 3.7+).

Install required packages:
```bash
pip install pygame numpy
