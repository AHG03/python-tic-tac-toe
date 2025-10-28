# 🐍 Command-Line Tic-Tac-Toe Game ❌⭕

A simple, two-player command-line implementation of the classic game Tic-Tac-Toe, built in Python.

## ✨ Features

* **Colored Marks:** Uses the **`termcolor`** library to display 'X' (red) and 'O' (green) on the board for better visual clarity.
* **Clear Board Display:** A clean, easy-to-read board is printed after every move.
* **Input Validation:** Robust input handling ensures players enter valid row and column numbers (0-2) and prevents moves on spots that are already taken.
* **Win/Tie Detection:** Automatically checks for all possible win conditions (rows, columns, and diagonals) and announces a winner or a draw (full board).

---

## 🚀 How to Run

### Prerequisites

You need **Python 3.x** installed on your system.

This project relies on the **`termcolor`** library for colored output. You must install it using pip:

```bash
pip install termcolor
````

### Execution

1.  Clone this repository or ensure the `tic_tac_toe.py` file is saved locally.
2.  Open your terminal or command prompt.
3.  Navigate to the directory where the file is located.
4.  Run the game using the Python interpreter:

<!-- end list -->

```bash
python tic_tac_toe.py
```

### Gameplay

  * The game starts with **Player X** (displayed in red).
  * Players take turns entering the **row** and **column** (values from 0 to 2) where they wish to place their mark.
  * The board is updated and printed after each valid move.
  * The game ends when a player achieves three in a row or the board is full.

-----

## ⚙️ Project Structure

The entire game logic is contained within a single file:

  * **`tic_tac_toe.py`**: Contains all game functions, including board drawing, player move logic, and the win/tie condition checks.

-----

## 🤝 Contributing

Contributions are welcome\! If you find bugs or have ideas for improvements (e.g., adding an AI opponent or different board sizes), please feel free to fork the repository and submit a pull request.

-----
