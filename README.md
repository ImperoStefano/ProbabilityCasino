# 🎰 Probability Casino — The House Always Wins

![React](https://img.shields.io/badge/React-18.2-blue.svg)
![Recharts](https://img.shields.io/badge/Recharts-2.15-ff69b4.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

An interactive probability and stochastic statistics laboratory, developed to visually and mathematically demonstrate the dynamics of gambling and the inevitability of the House Edge.

**🔗 [View Live Demo](https://ImperoStefano.github.io/ProbabilityCasino/)** *(Replace with your actual GitHub Pages link if different)*

## 🧠 Project Overview

This project models the outcomes of a European Roulette (37 slots), mathematically debunking myths related to betting strategies. Through real-time stochastic simulations running in the browser, the application illustrates advanced concepts such as:
* The **Law of Large Numbers (LLN)** and asymptotic convergence.
* The calculation of **Expected Value (EV)**.
* The **Risk of Ruin** in stochastic martingale systems.

## 🛠️ Core Features (Modules)

1. 🎡 **Roulette Lab** - Visual simulator with realistic wheel physics and geometry.
   - Dynamic tracking of bankroll, win rate, and financial flow history using vector charts.
   - Payout set to 1:1 to simulate *Even-Money* bets (Red/Black, Even/Odd, High/Low).

2. 📊 **Monte Carlo Room**
   - Engine for massive simulations (up to 100,000 simultaneous iterations).
   - Empirical demonstration of the mean converging to the European theoretical expected value: `E[X] = -1/37 ≈ -2.703%`.

3. ☠️ **Martingale Graveyard**
   - Parallel simulation of multiple independent players (random walks).
   - Visual demonstration of Gambler's Ruin: the doubling system inevitably fails when negative variance streaks hit the bankroll ceiling.

4. 🌍 **Bilingual Support (I18n)**
   - Fully reactive interface in English and Italian, with real-time text and chart updates without page reloads.

## 💻 Tech Stack

The project is architected to be **extremely lightweight and resilient**. It requires no build process (NPM, Webpack, or Vite) and circumvents local dependency issues (CORS).
- **Frontend Core:** React 18 & ReactDOM
- **Transpilation:** Babel Standalone (on-the-fly JSX compilation)
- **Data Visualization:** Recharts (SVG Charts)
- **Styling:** Pure CSS3 with animations and a minimalist dark mode design.

## 🚀 Setup & Execution

Since the application is built as a self-sufficient, single-file architecture, setup is immediate:

### Method 1: Local
1. Clone this repository: `git clone https://github.com/your-username/ProbabilityCasino.git`
2. Simply double-click the `index.html` file to open it in your preferred browser. No local server is required.

### Method 2: GitHub Pages
The *Zero-Build* architecture makes deployment instantaneous:
1. Go to **Settings** > **Pages** in your GitHub repository.
2. Select the `main` branch and the `/` (root) folder.
3. The application will be live and functional in less than a minute.

## 👨‍💻 Author

**Stefano Kolta**
Designed and developed for research and mathematical verification purposes.

---
*“You thought you beat probability. Probability disagreed.”*
