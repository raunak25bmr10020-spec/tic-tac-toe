# Tic-Tac-Toe (Console) — Simple Two-Player Game

## Project Title
Tic-Tac-Toe Console Game

## Overview
A simple console-based Tic-Tac-Toe game implemented in Python. Two players (X and O) alternately enter cell indices (0–8) to place their mark. The game displays the board after every move and checks for win conditions.

This project demonstrates modular programming, input validation, game logic, and a simple user interface — aligning with course learning outcomes for hands-on implementation and documentation. The project follows the Build Your Own Project submission guidelines. (See project brief at `/mnt/data/BuildYourOwnProject.pdf`.) :contentReference[oaicite:1]{index=1}

## Features
- Two-player Tic-Tac-Toe playable via the terminal.
- Clear board rendering after every move.
- Win detection for all standard lines (rows, columns, diagonals).
- Input validation and turn management.
- Modular structure (separate files suggested for logic, UI, and runner).

## Technologies / Tools Used
- Language: Python 3.8+
- Version control: Git (recommended)
- Optional: VS Code or any code editor for development and testing

## Project Structure (recommended)
tic-tac-toe/
├── README.md
├── statement.md
├── requirements.txt # (empty or contains e.g. python version notes)
├── src/
│ ├── main.py # runner / CLI loop
│ ├── game_logic.py # win check, game state updates
│ ├── ui.py # printBoard and input helpers
│ ├── validators.py # input validation utilities
│ └── utils.py # small helpers (e.g., sum replacement)
├── tests/
│ ├── test_game_logic.py
│ └── test_validators.py
└── project_report.pdf # final project report (upload to portal)


> Notes: The provided code can be split into the files listed above to meet the "minimum 5-10 modules/files" requirement.

## Non-functional Requirements
- **Performance:** Instant board updates and win checks (constant-time checks per move).
- **Usability:** Clear prompts, numbered board cells, and helpful error messages.
- **Reliability:** Prevent overwriting already filled cells; handle invalid inputs gracefully.
- **Maintainability:** Modular source layout, with comments and docstrings for functions.

## How to install & run
1. Ensure Python 3.8 or later is installed.
2. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd tic-tac-toe

Run the game:

python src/main.py


Follow on-screen prompts to play (enter a number 0–8 representing the cell).

Testing

Unit tests for game_logic should verify:

Win detection for X and O across all winning triplets.

No false positives on incomplete states.

Tests for validators should verify:

Reject invalid inputs (non-integer, out-of-range).

Reject moves on already taken cells.

Run tests:

pytest tests/

Screenshots

(You may add terminal screenshots here to demonstrate gameplay.)

Notes / Future Enhancements

Add AI opponent (minimax) for single-player mode.

Improve UI (colored output or simple GUI with Tkinter).

Add game replay/save feature and match statistics.

Add logging and more extensive unit tests.

References

Project brief: /mnt/data/BuildYourOwnProject.pdf. 

BuildYourOwnProject


