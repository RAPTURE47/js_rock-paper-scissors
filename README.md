# ✊✋✌️ Stone Paper Scissors

A browser-based **Stone Paper Scissors** game played over **5 rounds** against the computer. Built with plain HTML and vanilla JavaScript — no libraries, no frameworks, just the basics.

---

## 🎮 How to Play

1. Open `index.html` in any web browser
2. For each of the 5 rounds, a prompt will appear asking for your choice:
   - Enter `1` → Rock
   - Enter `2` → Paper
   - Enter `3` → Scissors
3. The computer picks randomly
4. Round result is logged in the **browser console**
5. After 5 rounds, the final score and winner are announced

> 💡 Open the browser console (`F12` → Console tab) to see the game output

---

## 🕹️ Game Rules

| You       | Computer  | Result      |
|-----------|-----------|-------------|
| Rock      | Scissors  | You win ✅  |
| Paper     | Rock      | You win ✅  |
| Scissors  | Paper     | You win ✅  |
| Rock      | Paper     | You lose ❌ |
| Scissors  | Rock      | You lose ❌ |
| Paper     | Scissors  | You lose ❌ |
| Any       | Same      | Tie 🤝      |

---

## 📁 Project Structure

```
stone-paper-scissors/
└── index.html       # All game logic (HTML + JavaScript)
```

---

## 🚀 Getting Started

No installation needed. Just clone and open:

```bash
git clone https://github.com/your-username/stone-paper-scissors.git
cd stone-paper-scissors
open index.html
```

---

## 🧠 How It Works

| Function           | Description                                      |
|--------------------|--------------------------------------------------|
| `getComputerChoice()` | Generates a random choice for the computer    |
| `getHumanChoice()`    | Prompts the player for input each round        |
| `playRound()`         | Compares choices and updates scores            |
| `playGame()`          | Loops through 5 rounds and drives the game    |

---

## 🛠️ Built With

- HTML5
- Vanilla JavaScript

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
