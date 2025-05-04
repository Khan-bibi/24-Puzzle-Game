# 24-Puzzle Game

A console-based 24-puzzle game implemented in C++. This game challenges the player to arrange tiles in the correct order using legal moves, starting from a randomized but solvable board state.

---

## 🎮 Features

- New game with randomly generated board
- Load previous game using your game ID
- Save progress automatically
- Shows valid moves (up, down, left, right)
- Tracks path of moves taken
- Fun console UI using Windows API for color

---

## 🛠️ Technologies Used

- **Language:** C++
- **Platform:** Windows
- **Libraries:** `windows.h`, `conio.h`, `ctime`, `fstream`

---

## 🚀 How to Play

1. Run the program.
2. Choose from:
   - **New Game**: Generates a new solvable 24-puzzle.
   - **Load Game**: Load saved progress using your unique ID.
   - **How to Play?**: Displays instructions.
3. Make moves using valid key inputs shown.
4. Press `1` during gameplay to save and exit.

---

## 📂 File Requirements

- `ids.txt`: Make sure this file exists in the same folder as `24PuzzleGameCode.cpp`. It stores saved IDs.

---

## 🧠 Future Improvements

- Cross-platform support
- GUI version
- Move counter and scoring
- AI Solver

---

## 🔖 Author

Made by [Your Name].

