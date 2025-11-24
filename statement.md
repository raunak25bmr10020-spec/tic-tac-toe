# Project Statement — Tic-Tac-Toe Console Game

## 1. Introduction
This project implements a simple two-player Tic-Tac-Toe game using Python.  
The game runs in the console and allows players X and O to take turns entering their moves.  
It demonstrates fundamental programming concepts such as lists, conditional logic, loops, modular functions, and user interaction.

The project is designed according to the requirements mentioned in the course’s *Build Your Own Project* guidelines and serves as an introductory practical application of Python-based problem solving.

---

## 2. Problem Statement
Tic-Tac-Toe is a classic 3×3 grid game in which two players alternate marking spaces until one achieves three in a row or all spaces fill, resulting in a draw.

The goal of this project is to:
- Simulate the game through a command-line interface.
- Allow players to enter positions interactively.
- Visually render the board after each turn.
- Detect winning conditions and end the game appropriately.

---

## 3. Objectives
The main objectives of the project are:
1. To design and implement a modular Python program with separate functions for board display and win detection.
2. To provide clear interaction between the user and the console.
3. To develop a functioning win-checking algorithm for row, column, and diagonal patterns.
4. To apply programming concepts such as loops, conditionals, arrays, and function calls.

---

## 4. Scope of the Project
### In-Scope
- Two-player Tic-Tac-Toe (Player X and Player O).
- Rendering the game board after every move.
- Validating winning states using predefined combinations.
- Providing clear game messages such as:
  - Whose turn it is
  - Which player won
  - Match over notification

### Out-of-Scope
- Artificial Intelligence (AI) or single-player mode.
- Graphical User Interface (GUI).
- Network or multiplayer online gameplay.
- Persistent data storage.

---

## 5. Proposed System
The game is structured using the following components:

### **1. Board Printing Module**
Displays the current state of the 3×3 board after every move using characters X, O, or the respective index number for empty cells.

### **2. Game Logic Module**
Contains:
- `sum()` helper function  
- `checkWin()` function to evaluate all 8 possible winning combinations  
- Lists representing X and O moves (`xState` and `zState`)

### **3. Main Execution Loop**
Controls:
- Turn alternation  
- Input collection  
- Board rendering  
- Game termination after win/draw  

---

## 6. System Flow (Summary)
1. Initialize game states for X and O.  
2. Start game loop.  
3. Print board.  
4. Ask current player for input.  
5. Update their corresponding state list.  
6. Check for win.  
7. If win detected → display result and terminate.  
8. Else, switch turn and continue.

---

## 7. Functional Requirements
1. **FR1:** The system must allow two players (X and O) to play alternately.  
2. **FR2:** The system must display the game board after every move.  
3. **FR3:** The system must detect winning patterns across:
   - Rows  
   - Columns  
   - Diagonals  
4. **FR4:** The game must stop immediately once a win occurs.  
5. **FR5:** The system must inform the players about whose turn it is.

---

## 8. Non-Functional Requirements
1. **Usability:**  
   - The board layout must remain simple and readable.  
   - User prompts must be clear.

2. **Performance:**  
   - Win checking should be instantaneous (constant time).  

3. **Maintainability:**  
   - Code should be modular with separate functions.  
   - Easy to extend for future upgrades (AI, GUI, etc.).

4. **Reliability:**  
   - Game logic must correctly detect all winning states.

---

## 9. Tools & Technology
- **Programming Language:** Python 3  
- **Editor (optional):** VS Code / PyCharm / Sublime  
- **Execution:** Command-line terminal

---

## 10. Conclusion
The Tic-Tac-Toe Python console game successfully demonstrates the practical application of core programming concepts. It also lays a solid foundation for enhancements such as AI opponents, error handling, GUI development, or online multiplayer.  
This project is ideal as a beginner-level programming exercise and clearly fulfills the intended learning outcomes.

