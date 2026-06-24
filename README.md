# 🎰 Probability Casino — The House Always Wins

![React](https://img.shields.io/badge/React-18.2-blue.svg)
![Recharts](https://img.shields.io/badge/Recharts-2.15-ff69b4.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

[![🎰 Live Demo](https://img.shields.io/badge/🎰_Live_Demo-Probability_Casino-dc2626?style=for-the-badge)](https://ImperoStefano.github.io/ProbabilityCasino/)

An interactive probability lab that simulates European Roulette, Monte Carlo convergence, martingale strategies, and Blackjack — all running in the browser to show why the house edge is inevitable.

---

## 🧠 What It Demonstrates

- **Law of Large Numbers** – empirical mean converges to the theoretical EV (−2.70%)
- **Expected Value** – every bet has a negative expectation
- **Risk of Ruin** – progressive betting systems eventually fail
- **Strategy Comparison** – Flat, Martingale, Anti‑Martingale, D’Alembert, Fibonacci

---

## 🎮 Modules

| Module | Description |
|--------|-------------|
| 🎡 **Roulette Lab** | Spin a realistic wheel, place outside/inside bets, track bankroll history |
| 📊 **Monte Carlo Room** | Run up to 100k simulations of betting on Red |
| ☠️ **Martingale Graveyard** | Simulate 20 players doubling after losses — watch them go bust |
| 🧮 **Strategy Lab** | Compare 5 staking systems over thousands of trials, with ruin charts and stats |
| 🃏 **Blackjack Engine** | Play European Blackjack with basic strategy hints, splits, and insurance |

---

## ⚙️ Tech Stack

**Zero build, single HTML file.** No NPM, no Webpack, no server needed.

- React 18 (via CDN)
- Recharts for SVG charts
- Babel Standalone for on‑the‑fly JSX
- Web Audio API for sound effects
- localStorage for progress persistence
- Bilingual (English / Italian)

---

## 🚀 How to Run

1. Clone or download the repository
2. Open `index.html` in any modern browser

To deploy on GitHub Pages, just point the Pages source to the `main` branch root folder.

---

## 👤 Author

**Stefano Kolta**

*“You thought you beat probability. Probability disagreed.”*
