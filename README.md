# ♠️ Card Counting Assistant

A beginner-friendly JavaScript project that simulates the card counting strategy used in Blackjack. The program tracks the running count of cards and advises whether the player should **Bet** or **Hold**.

## ✨ Features

- Tracks a global card count
- Processes both numeric and face cards
- Implements basic Blackjack card counting rules
- Returns betting recommendations based on the current count
- Beginner-friendly JavaScript practice project

## 🛠️ Technologies Used

- JavaScript

## 📜 Card Counting Rules

| Card | Count Change |
|--------|------------|
| 2, 3, 4, 5, 6 | +1 |
| 7, 8, 9 | 0 |
| 10, J, Q, K, A | -1 |

## 📜 Example

```js
cardCounter(2);
cardCounter(3);
cardCounter(4);
cardCounter(5);
console.log(cardCounter(6));
```

Output:

```bash
5 Bet
```

## 🚀 How to Run

1. Save the code in a file named `cardCounter.js`
2. Open a terminal in the project folder
3. Run:

```bash
node cardCounter.js
```

## 📚 Concepts Practiced

- Variables (`let`)
- Functions
- Conditional statements (`if...else`)
- Global state management
- String concatenation
- Blackjack card counting logic

## 🎯 Purpose

This project was created as a beginner JavaScript exercise to practice functions, conditionals, and implementing real-world game logic.

## 👨‍💻 Author

Kumari Khushi
