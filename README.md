# 👑 Kallanum Policeum · Royal Deduction Game

🔗 **Play the game here:**
[https://anzafathima-jm.github.io/kallanum_policeum_version_2/](https://anzafathima-jm.github.io/kallanum_policeum_version_2/)

---

## 🧾 Project Review (v2.x)

**Kallanum Policeum** is a polished, pass-and-play social deduction game with a strong visual identity and a clear gameplay loop. The current version focuses on a royal hierarchy system, strategic guessing, and score-based progression.

### ✅ Strengths

* Consistent **royal-themed UI** with high visual polish
* Clear **hierarchy-based gameplay** that scales with player count
* Smooth **animations and sound effects** that enhance feedback
* Fully **client-side** and works offline
* Mobile-responsive and touch-friendly

### 🔧 Areas for Future Improvement

* Prevent duplicate player names (use internal IDs)
* Optional in-game **How to Play** screen for first-time users
* Accessibility improvements (non-color cues, keyboard support)

---

## 🎮 About the Game

**Kallanum Policeum** is a local multiplayer social deduction game inspired by the traditional *Kallan & Police* concept, redesigned with a **royal hierarchy** and modern game mechanics.

Players secretly receive roles, reveal them privately, and then attempt to deduce the hierarchy in order. Correct guesses earn points, while wrong guesses cause role swaps, creating tension and mind games.

Designed for **4–11 players**, played on a single device.

---

## 🏰 Role Hierarchy (Max 11 Players)

| Order | Role         | Points |
| ----: | ------------ | ------ |
|     1 | 👑 King      | 1000   |
|     2 | 👸 Queen     | 500    |
|     3 | 🧠 Manthri   | 400    |
|     4 | ⚔️ Commander | 350    |
|     5 | 🗡️ Soldier  | 300    |
|     6 | 👀 Watchman  | 250    |
|     7 | 🕶️ Spy      | 200    |
|     8 | 🌿 Gardener  | 150    |
|     9 | 🥛 Milkman   | 100    |
|    10 | 🚔 Police    | 50     |
|    11 | 🕵️ Thief    | 0      |

> Roles are automatically selected based on player count.

---

## 🧠 Game Flow

### 1️⃣ Setup Phase

* Add **4–11 players**
* Enter player names
* Roles are shuffled and assigned secretly

### 2️⃣ Reveal Phase

* Each player privately reveals their role
* Device is passed to the next player

### 3️⃣ King Reveal

* The King reveals their identity
* Deduction phase begins

### 4️⃣ Guess Phase

* Active role must guess who holds the **next role in hierarchy**
* ✅ Correct guess → earn points equal to role value
* ❌ Wrong guess → **roles swap**, changing the game state

### 5️⃣ Round End

* Round scores are displayed
* Continue to the next round or view final rankings

---

## ✨ Features

* 🎭 Dynamic role assignment
* 🔄 Role swapping on incorrect guesses
* 📊 Persistent scoring across rounds
* 🔊 Sound effects via Web Audio API
* 🎨 Royal-themed custom UI
* 📱 Mobile-friendly & responsive
* ⚡ Fully offline & client-side

---

## 🛠 Tech Stack

* HTML5
* CSS3 (Custom Royal Theme)
* Vanilla JavaScript
* Web Audio API

---

## 🚀 How to Play / Run

### ▶ Play Online

Open the live version:

```
https://anzafathima-jm.github.io/kallanum_policeum_version_2/
```

### ▶ Run Locally

1. Clone or download the repository
2. Open `index.html` in any modern browser

---

## 📂 Project Structure

```
index.html
README.md
```

---

## 🔮 Planned Enhancements

* In-game How-to-Play screen
* Role-based visual indicators
* Accessibility improvements
* Online multiplayer experiment

---

## 📜 License

© 2026 Anza Fathima. All rights reserved.

This project is publicly accessible for **demonstration, portfolio showcase, and gameplay purposes only**.

The source code, design, game logic, visual assets, and overall concept **may not be copied, modified, redistributed, reverse-engineered, or used for commercial purposes** without explicit written permission from the author.

---

## 👤 Author

Created by **Anza Fathima (Aifu)**
Independently designed and developed as a portfolio project, a future commercial concept, and a passion-driven game experiment 👑
