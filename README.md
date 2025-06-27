# 🎮 TicTacToe-OOP-Design

A fully object-oriented C++ implementation of a customizable Tic Tac Toe game using **SOLID principles** and popular **Design Patterns** like:

- ✅ Observer Pattern (Notification system)
- ✅ Strategy Pattern (Rule implementation)
- ✅ Factory Pattern (Game creation)

---

## 📌 Features

- 🎯 Custom board size (e.g., 3x3, 4x4, etc.)
- 👥 Multi-player support (2 players)
- 🧠 Clear separation of concerns using OOP principles
- 🛠️ Easy to extend with new game rules
- 🔔 Console notification using Observer pattern

---

## 🔧 Design Patterns Used

| Pattern      | Purpose                                                                 |
|--------------|-------------------------------------------------------------------------|
| Observer     | To notify users of game events (e.g., move played, win, draw)           |
| Strategy     | To encapsulate game rule logic (win, draw, valid move checks)           |
| Factory      | To abstract and centralize game object creation                         |

---

## 🧩 Class Structure Overview

- `Board`: Manages game grid and mark placements
- `Symbol`: Represents player marks (`X`, `O`, etc.)
- `TicTacToePlayer`: Contains player information and symbol
- `TicTacToeRules` + `StandardTicTacToeRules`: Game rules using Strategy pattern
- `TicTacToeGame`: Core gameplay loop with observers
- `IObserver` + `ConsoleNotifier`: Implements Observer pattern for notifications
- `TicTacToeGameFactory`: Factory pattern for game creation

---

## 🚀 How to Run

### Step 1: Clone the Repository
```bash
git clone https://github.com/your-username/TicTacToe-OOP-Design.git
cd TicTacToe-OOP-Design
