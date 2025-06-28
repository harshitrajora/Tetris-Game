# 🎮 Tetris Game

A classic **Tetris clone** developed in **C++** using the **Raylib graphics library**. Built with object-oriented principles, clean game loop architecture, and smooth gameplay.

---

## 🚀 Features

- ✅ Classic Tetris mechanics  
- 🎨 Raylib-based visual rendering  
- 🎮 Smooth block movement & rotation  
- 🧠 OOP architecture for maintainability  
- 📦 Released and playable version

---

## 🎮 How to Play

| Action           | Key               |
|------------------|-------------------|
| Move Left/Right  | ← / → arrow keys  |
| Soft Drop        | ↓ arrow key       |
| Hard Drop        | Spacebar          |
| Rotate Block     | Z / X             |
| Quit             | ESC               |

---

## 📥 Play Now

### 🔗 [Download Latest Release](https://github.com/harshitrajora/Tetris-Game/releases)

> Pre-built executable for Windows/Mac/Linux available in Releases.

---



## 🛠️ Build from Source

> Requirements: C++ Compiler, Raylib installed

![Gameplay](assets/Gameplay.png)
![Game Over](assets/Gameover.png)

### 🔧 Steps:
```bash
git clone https://github.com/harshitrajora/Tetris-Game.git
cd Tetris-Game
brew install raylib           # Install raylib (if not already installed)
g++ src/main.cpp -o Tetris -lraylib -std=c++17 -framework OpenGL -framework Cocoa -framework IOKit -framework CoreAudio
./Tetris

