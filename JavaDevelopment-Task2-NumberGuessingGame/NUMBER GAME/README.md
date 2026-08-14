# 🎮 Number Guessing Game - Java Console Application

A feature-rich, object-oriented console-based number guessing game built in **Java**. Players can choose from multiple difficulty tiers, track their wins and losses, input personalized usernames, and review detailed round summaries.

---

## ✨ Features

* **Custom User Profiles**: Prompts the user to set up a personalized gamer profile upon startup.
* **Multiple Difficulty Modes**:
  * **Easy**: Range 1–50 with 10 attempts.
  * **Medium**: Range 1–100 with 7 attempts.
  * **Hard**: Range 1–200 with 5 attempts.
* **Score & Stats Tracking**: Automatically records total wins, losses, and detailed round-by-round history summaries.
* **Robust Input Validation**: Error-handling logic to prevent crashes from invalid strings, out-of-range guesses, or bad formatting.

---

## 🛠️ Tech Stack

* **Language:** Java
* **Libraries Used:** `java.util.Scanner`, `java.util.Random`, `java.util.ArrayList`, `java.util.List`

---

## 📂 Project Structure

```text
NUMBER GAME/
│
├── src/
│   └── main/
│       └── java/
│           └── NoGame.java    # Core game loop, menus, and validation logic
│
└── README.md
