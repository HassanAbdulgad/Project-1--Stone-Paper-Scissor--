# 🎮 Stone-Paper-Scissor Game

A simple command-line game where the player competes against the computer in the classic **"Stone, Paper, Scissors"**. The computer generates its choice randomly, and the game compares it with the player's choice to determine the winner over multiple rounds.

---

## 📖 About the Project

This project is designed as a foundational exercise to practice and demonstrate mastery of essential programming concepts in C++. The core goals were to implement and understand:

1.  **Conditional Statements:** Used to accurately determine the winner of each round and the overall game (e.g., if Player chooses Stone and Computer chooses Scissors, Player wins).
2.  **Loops:** Used for controlling the main game flow, allowing for multiple rounds, and providing the option to play the game again.
3.  **Random Number Generation:** Used to ensure the computer's choice is unpredictable by using the system time as a seed for true randomness.
4.  **Functions:** Structuring the entire program into reusable, modular blocks (e.g., functions for reading player input, generating computer choice, determining the winner, and displaying results).

---

## ✨ Features and Game Logic

The application implements robust game logic, providing:

* **Multi-Round Play:** The user specifies the total number of rounds to play at the start of the game.
* **Automatic Score Tracking:** The system keeps a running tally of wins for the Player, Computer, and the total number of Draws.
* **Input Validation:** Ensures the player can only enter `1`, `2`, or `3` as choices.
* **Final Result Determination:** Declares the overall game winner based on the highest number of rounds won.

---

## 🛠 Built With

| Technology / Library | Purpose |
| :--- | :--- |
| **C++** | Core programming language for the entire application. |
| **`<iostream>`** | Handles command-line input/output (displaying score, reading user choice). |
| **`<cstdlib>`** | Provides the `rand()` and `srand()` functions for random number generation. |
| **`<ctime>`** | Provides the `time()` function, used to seed the random generator for unpredictability. |

---

## 🎓 Training Track Reference

This project was developed as part of the **AbouHadhood Platform** training track, under the guidance of **Dr. Mohamed Abou Hadhoud**.
