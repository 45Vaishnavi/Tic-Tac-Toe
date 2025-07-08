# 🎮 Tic-Tac-Toe: Human vs Computer (C++ Console Game)

This is a fun and interactive command-line **Tic-Tac-Toe** game built in C++. You play as the human (`O`) against a simple AI (`X`) which tries to block your moves. The game includes a visual board, instructions, and automatic game resets after each round.

---

## 🕹️ How to Play

- You play first as `O`, and the machine plays second as `X`.
- Enter the number (1-9) corresponding to the position on the board where you want to place your symbol.
- The board and keymap are shown side-by-side for easy input reference.
- The machine responds automatically with a move based on basic logic and randomness.
- After every round (win, lose, or tie), the game resets and continues.

---

## 🧠 AI Logic

The machine uses a combination of:
- **Blocking logic** (tries to prevent you from winning)
- **Random moves** when no immediate threat is detected

---

## 🎯 Features

- Clean and interactive CLI interface using `system("CLS")`
- Real-time game board display
- Simple AI logic (hardcoded checks + randomness)
- Automatic game loop using `goto` (old-school but functional)
- Displays winner, tie, and prompts for replay

---

## 💻 How to Run

### 🧑‍💻 Compile and Run using g++

```bash
g++ tictactoe.cpp -o tictactoe
./tictactoe
```

💡 Works best on **Windows** since it uses `windows.h` and `system("CLS")` for screen clearing.

---

## 📦 Requirements

- Windows OS
- C++11 or above
- Compatible compiler (e.g., g++, Code::Blocks, Visual Studio)

---

## 🛠️ Future Improvements (Optional)

- Replace `goto` with loops/functions for better structure
- Add minimax AI for smarter gameplay
- Add score tracking
- GUI version using a graphics library (SFML, SDL, etc.)
- Cross-platform compatibility

---

## 👨‍💻 Author

Developed by Vaishnavi

A simple and fun C++ project for beginners to understand game logic, AI basics, and terminal interaction.

---
