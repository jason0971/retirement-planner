# 🎯 Retirement Flight Deck & Independence Simulator

An institutional-grade, standalone financial planning and retirement simulator for UK investors.

Designed to model multi-wrapper growth (**SIPPs, Workplace Pensions, Stocks & Shares ISAs**), decumulation runway, HMRC income tax rules (personal allowance + 25% tax-free PCLS cash), and State Pension integration from today through later life (to Age 85).

---

## 🚀 Quick Start

1. **Open `index.html`** in any web browser (Google Chrome, Safari, Edge, Firefox).
2. No internet server, dependencies, or installations required — the simulator runs 100% locally on your computer with complete privacy.

---

## 📑 What's Included

The dashboard includes 7 dedicated tabs:

1. **📊 Headline & Valuations:** Instant net worth breakdown, target milestone progress, asset allocation (Equities vs. Defensive Cash Buffer), and account summaries.
2. **📈 Performance & Holdings:** Granular view of individual index funds, ETFs, unit counts, cost basis, uninvested cash interest, and wrapper categories.
3. **🌉 Retirement Bridge (Ages 57 ➔ 67):** Models the critical 10-year gap between early retirement and UK statutory State Pension age, including monthly cashflow tracking and asset preservation.
4. **🏛️ Tax & Drawdown Playbook:** Explains and calculates HMRC UFPLS rules (taking 25% tax-free cash alongside the £12,570 personal allowance to achieve low single-digit effective tax rates).
5. **🛡️ Stress Tests & Advice:** Historical crash simulations (e.g. 2008 GFC, 2000 Dot-Com, 1970s stagflation), asset rebalancing recommendations, and safe withdrawal rate (SWR) rules.
6. **⏳ Life Simulator to Age 85:** An interactive actuarial playground with live sliders for spending (£20k–£75k/yr), real returns, State Pension offsets, and crash shocks with live Depletion Age calculation.
7. **📑 Pension Tracker & Multi-Scenario Forecaster:** Compares 4 simultaneous compounding market curves (3% Conservative, 5% Balanced, 7% Growth, 10% Aggressive) and visualizes the early-retirement decumulation **"U-Dip"** trough before State Pension activation.

---

## 🛠️ How to Customize with Your Own Numbers

### Method 1: Interactive Sliders (Fastest)
Simply drag the interactive sliders across **Tab 6 (Life Simulator)** and **Tab 7 (Pension Tracker)** to test different spending targets, return assumptions, and State Pension options.

### Method 2: Edit `portfolio_data.json`
If you want the dashboard to open with your actual portfolio values:
1. Open `portfolio_data.json` in any text editor.
2. Edit the accounts, values, holdings, and targets.
3. Refresh `index.html` in your browser.

---

## 🔒 Privacy & Security
All calculations are performed locally in JavaScript on your machine. No financial data is sent to external servers or cloud services.
