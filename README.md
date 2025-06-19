# Tic-Tac-Toe (Local Multiplayer) in C using Ncurses

This is a simple terminal-based Tic-Tac-Toe (Tris) game written in C using the `ncurses` library. It supports two human players taking turns on the same keyboard.

## 🎮 Features

- 2-player local multiplayer (Player X vs Player O)
- Clear terminal interface using `ncurses`
- Input via keyboard (row and column)
- Detects win and draw conditions
- Logs each completed game in `score.txt`

## 🧰 Requirements

- C Compiler (e.g. `gcc`)
- `ncurses` library

### Install Ncurses (Linux)

```bash
sudo apt install libncurses5-dev libncursesw5-dev
```

### ⚙️ Compilation (Linux)

```bash
make
```

### ▶️ Run the Game

```bash
./tris
```
### 🗂️ Project Structure

```bash
tris-multiplayer/
├── main.c         # Main menu and interface
├── logic.c/h      # Game logic (board, moves, win check)
├── score.c/h      # Game result logging
├── Makefile       # Build instructions
├── score.txt      # Game logs
└── README.md      # This file
```
