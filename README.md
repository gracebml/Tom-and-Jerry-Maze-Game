# 🧩 TOM AND JERRY – Maze Game

> Final Project – **Programming for Artificial Intelligence**  
> Faculty of Information Technology – University of Science, VNU-HCM  
> **Class:** 23TNT1  
> **Instructor:** Nguyễn Trần Duy Minh  

---

## 📖 Overview

**TAM AND GIA HUY** is a maze-solving game that demonstrates how **AI pathfinding algorithms** work in real-time.  
The project applies core concepts of artificial intelligence and algorithm visualization to create an interactive and educational game experience.

Built with **Python**, the game uses **Pygame** and **Tkinter** to provide a complete graphical interface, animation, sound system, and multiple gameplay modes — from manual control to full AI automation.

---

## ⚙️ Technologies

- **Language:** Python 3.10+
- **Libraries:**  
  - `pygame` – main game engine  
  - `tkinter` – UI forms and dialogs  
  - `pyautogui`, `threading`, `queue`, `os`, `random`, `time`
- **Algorithms:**  
  - DFS, BFS, Dijkstra, A*  
  - Randomized Maze Generation (DFS-based)

---

## 🧠 Main Features

### 🕹️ Gameplay
- Player-controlled character navigating the maze  
- **AI Auto-Play Mode** – bot solves the maze using selected algorithms  
- **Path Suggestion** and **Visualization Mode** to show algorithm behavior

### 💾 Save & Load
- Full **Save/Load system** with `database.json` and `ranking.json`  
- **Leaderboard** updates automatically after each playthrough

### 🎨 Interface
- Main Menu, Login/Register, Dashboard, Pause/Resume, Transition effects  
- Win/Lose screens, Mini-map, Loading animation  
- All custom-built with Pygame graphics

### 🔊 Audio
- Background music and sound effects  
- Player can toggle sound anytime during gameplay
  
---

## 🚀 How to Run

### 1️⃣ Install dependencies
```bash
pip install pygame pyautogui

python main.py

---

📅 Completed: April 2024 – Ho Chi Minh City
👨‍🎓 Team 1 – Programming for Artificial Intelligence (HCMUS)
