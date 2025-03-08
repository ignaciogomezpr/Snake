# 🐍 Snake Game - Code Challenge

## Overview
This repository contains a simple implementation of the classic **Snake** game. The challenge includes reading and writing the high score to a file to maintain a persistent record of the player's best performance.

## 🚀 How to Run
1. **Clone** this repository:
   ```bash
   git clone https://github.com/ignaciogomezpr/Snake.git
   ```
2. **Navigate** to the project directory:
   ```bash
   cd Snake
   ```
3. **Run** the game script:
   ```bash
   python snake.py
   ```

## 📌 Requirements
- 🐍 **Python 3.x** (Download it here: [Python Download](https://www.python.org/downloads/))
- 🎨 **Pygame** (if using a graphical version)
  ```bash
  pip install pygame
  ```

## Features
-  **Score tracking**
-  **Persistent high score saved to a file**
-  **Classic Snake game mechanics**

## 🔧 How It Works
1. The game starts with a default score of `0`.
2. The snake grows and the score increases as it eats food.
3. When the game ends, the current score is compared to the stored high score.
4. If the current score is higher, it is written to the high score file.
5. The high score is read from the file at the beginning of each game session.

## 📂 File Handling
- **`high_score.txt`**: A simple text file where the highest score is stored.
- The program **reads** from this file when the game starts.
- If a **new high score** is achieved, it overwrites the previous value.

## 🏆 Code Challenge Task
- ✅ Implement **reading and writing** the high score to a file.
- ✅ Ensure that the game **retrieves the high score** correctly at startup.
- ✅ Update the high score **only when a new record** is set.

## 🤝 Contributions
Feel free to **fork** this repository and **submit pull requests** with improvements or additional features!

## 📜 License
This project is **open-source** and available under the **MIT License**.

[🔗 GitHub Repository](https://github.com/ignaciogomezpr/Snake.git)

