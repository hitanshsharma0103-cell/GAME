# Tic-Tac-Toe Game 🎮

A classic console-based Tic-Tac-Toe game implemented in Python. Play against a friend in this timeless two-player game!


## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [How to Play](#how-to-play)
- [Game Rules](#game-rules)
- [Screenshots](#screenshots)
- [Code Structure](#code-structure)
- [Testing](#testing)
- [Future Enhancements](#future-enhancements)
- [Contributing](#contributing)
- [Author](#author)

## 🎯 About

This is a simple yet fully functional implementation of the classic Tic-Tac-Toe game in Python. The game runs in the console and allows two players to compete against each other. It features input validation, win detection, and a clean user interface.

## ✨ Features

- 🎲 **Two-Player Mode**: Play against a friend on the same computer
- 🎨 **Clean Console Interface**: Easy-to-read game board display
- ✅ **Input Validation**: Comprehensive error handling for invalid inputs
- 🏆 **Win Detection**: Automatic detection of all winning conditions
- 🤝 **Draw Detection**: Identifies when the game ends in a tie
- 🔄 **Turn Management**: Automatic player switching
- 💬 **User Feedback**: Clear messages for invalid moves and game outcomes

## 🚀 Getting Started

### Prerequisites

- Python 3.x or higher installed on your system

You can check your Python version by running:
```bash
python --version
```

### Installation

1. Clone the repository:
```bash
https://github.com/hitansharma/TIC-TAC-TOE.git
```

2. Navigate to the project directory:
```bash
Tic tac toe.py
```

3. Run the game:
```bash
Tic tac toe.py
```

That's it! No external dependencies required.

## 🎮 How to Play

1. Run the game using the command above
2. The game board is numbered 1-9 as follows:
   ```
   1 | 2 | 3
   --+---+--
   4 | 5 | 6
   --+---+--
   7 | 8 | 9
   ```
3. Player X goes first
4. Enter a number (1-9) to place your mark in that position
5. Players alternate turns
6. The first player to get three marks in a row (horizontally, vertically, or diagonally) wins
7. If all 9 positions are filled without a winner, the game is a draw

## 📖 Game Rules

- The game is played on a 3×3 grid
- Player X always goes first
- Players take turns placing their marks (X or O)
- The first player to get 3 of their marks in a row wins
- Winning combinations include:
  - **Horizontal**: Three marks in any row
  - **Vertical**: Three marks in any column
  - **Diagonal**: Three marks diagonally
- If all 9 squares are filled and no player has won, the game is a draw

## 📸 Screenshots

### Game Start
```
 |   | 
--+---+--
 |   | 
--+---+--
 |   | 

Player X, choose a position (1-9):
```

### Mid-Game
```
X | O | X
--+---+--
O | X |  
--+---+--
 |   | 

Player O, choose a position (1-9):
```

### Game Won
```
X | O | X
--+---+--
O | X | O
--+---+--
X |   | 

Player X wins!
```

## 🏗️ Code Structure

```python
# Main Components:

1. board (list): 3×3 game board representation
2. print_board(): Displays the current board state
3. check_winner(player): Checks if a player has won
4. Main game loop: Handles turns, input, and game flow
```

### Key Functions

- **`print_board()`**: Renders the game board in a user-friendly format
- **`check_winner(player)`**: Evaluates all winning combinations for a given player
- **Main Loop**: Manages game flow including:
  - Turn management
  - Input validation
  - Move execution
  - Win/draw detection

## 🧪 Testing

The game has been tested for various scenarios:

| Test Case | Description | Status |
|-----------|-------------|--------|
| Valid moves | Normal gameplay with valid inputs | ✅ Pass |
| Invalid range | Input outside 1-9 | ✅ Pass |
| Occupied position | Attempting to use taken spot | ✅ Pass |
| Non-numeric input | Letters or special characters | ✅ Pass |
| Win detection (row) | Horizontal win | ✅ Pass |
| Win detection (column) | Vertical win | ✅ Pass |
| Win detection (diagonal) | Diagonal win | ✅ Pass |
| Draw scenario | All positions filled, no winner | ✅ Pass |

## 🔮 Future Enhancements

- [ ] Add GUI using Tkinter or Pygame
- [ ] Implement single-player mode with AI opponent
- [ ] Add difficulty levels (Easy, Medium, Hard)
- [ ] Track game statistics and scores
- [ ] Add undo/redo functionality
- [ ] Implement network multiplayer
- [ ] Add customizable board sizes (4×4, 5×5)
- [ ] Include sound effects
- [ ] Add replay functionality

## 👤 Author

**Hitansh Sharma**
- Registration Number: 25BAI11433
- GitHub: https://github.com/hitansharma

## 🙏 Acknowledgments

- Inspired by the classic Tic-Tac-Toe game
- Thanks to the Python community for excellent documentation
- Special thanks to everyone who contributed to testing and feedback



---

⭐ If you found this project helpful, please consider giving it a star!

**Happy Gaming! 🎉**
