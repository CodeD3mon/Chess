# ♟️ Chess - Python Mini Game

This is a **basic Chess mini-game** made entirely from scratch using **Python** and **Pygame**. Whether you're a beginner looking to study how chess logic works or just want to play a quick match against a local opponent, this project is lightweight, clean, and fun!

---

## 🚀 Features

* Fully playable chessboard
* Piece movement and capturing
* Turn-based system (White vs Black)
* Simple and intuitive graphics using `pygame`
* Runs entirely offline

---

## 📦 Setup & Installation

### ✅ Step 1: Download the Files

* Download or clone this repository.
* Make sure you have the following two folders in the same directory:
  * `Chess/`
  * `assets/`

### 🔧 Step 2: Install Requirements

You must have Python installed (preferably Python 3.8+).

If any required packages are missing, run:

```bash
pip install -r requirements.txt
```

> If there's no `requirements.txt` file, manually install the only required dependency:
```bash
pip install pygame
```

---

## ▶️ How to Run

After setting everything up, just run the main Python file:

```bash
python Chess/main.py
```

The game window should open with a full chessboard and pieces ready to play.

---

## 🧩 Troubleshooting

* **Missing `pygame` Error**:  
  If you encounter the following error:
  ```
  ModuleNotFoundError: No module named 'pygame'
  ```
  Install pygame using:
  ```bash
  pip install pygame
  ```

* **Game Not Opening**:  
  Make sure you're not running the script in a restricted or terminal-only environment. A GUI is required.

---

## 💡 Suggestions & Contributions

This is a basic version. You can improve it by adding:

* AI opponent (minimax, stockfish, etc.)
* Move history and undo option
* Highlighting legal moves
* Game saving/loading
* Sound effects

---

## 👨‍💻 Made With ❤️ by Aayush Makkar

Feel free to fork the project, improve it, or use it as a base for your own chess engine!
