# 🕹️ Tic-Tac-Toe GUI Game (Python + Tkinter)

A simple and interactive **Tic-Tac-Toe (X/O)** game built using Python's Tkinter library. This game allows two players to play against each other on the same machine, with automatic win and tie detection.

---

## ✨ Features

- ✅ Graphical User Interface using `Tkinter`
- 🔄 Random player starts each game
- 🟩 Highlights winning combination in green
- 🟨 Tie detection with yellow-colored board
- 🔁 Restart button to play again
- 💡 No external libraries required

---

## 🚀 Getting Started

### Prerequisites

Ensure you have **Python 3.x** installed on your system. Tkinter comes pre-installed with standard Python distributions.

### Installation & Running

1. Clone this repository or download the `tic_tac_toe.py` file.
2. Run the script using Python:

```bash
python tic_tac_toe.py
```

### 🎮 How to Play

The game board is 3x3.

The game starts with a randomly selected player (X or O).

Click on an empty tile to place your mark.

The first player to align three marks (horizontally, vertically, or diagonally) wins.

If all tiles are filled without a winner, the game ends in a tie.

Click the Restart button to start a new round.

---

## 🧠 Code Overview

`next_turn(row, column)`: Handles game logic for each turn.

`check_winner()`: Checks rows, columns, and diagonals for a win or tie.

`empty_spaces()`: Counts empty tiles to determine a tie.

`new_game()`: Resets the game board and starts a new game.

---

## 📜 License

This project is licensed under the MIT License.
You are free to use, modify, and distribute it with attribution.
