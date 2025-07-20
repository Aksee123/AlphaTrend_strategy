# 📈 AlphaTrend Strategy

The **AlphaTrend Strategy** is a dynamic, trend-following Pine Script built for TradingView that leverages ATR volatility filtering and RSI momentum confirmation. This tool is ideal for traders looking to automate entries and exits with risk management built-in.

---

## ⚙️ Features

- **Trend Detection** using ATR and RSI logic
- **Smart Entry Signals** based on crossover logic
- **Dynamic Stop Loss / Take Profit** options
- Configurable **risk-to-reward ratios** and volatility filters
- Clean visual plotting for easy interpretation

---

## 🧠 Logic Summary

- **AlphaTrend Line** adapts based on RSI and ATR
- **Buy Signal**: when price crosses above AlphaTrend
- **Sell Signal**: when price crosses below AlphaTrend
- Risk can be managed via:
  - Swing highs/lows
  - Fixed percentage SL/TP
  - Optional 1:1 Risk to Reward mode

---

## 🛠️ Parameters

| Name            | Purpose                                  |
|----------------|-------------------------------------------|
| `Multiplier`    | Controls ATR sensitivity                 |
| `Common Period` | Used for RSI and ATR calculations        |
| `Price Source`  | Source for signal calculations           |
| `Use Fixed SL/TP` | Enables static stop-loss/take-profit  |
| `1:1 Risk to Reward` | Balances potential reward            |
| `SL / TP %`     | Percentage-based exits (if fixed mode)   |

---

## 📊 Plot Elements

- Blue line: AlphaTrend indicator
- Green triangle: Buy signal
- Red triangle: Sell signal

---

## 🚀 How to Use

1. Paste the script in TradingView's Pine Editor
2. Customize the parameters in the settings panel
3. Add to chart and backtest across different asset classes
4. Refine your entries using signal shapes and historical data

---

## 📁 File Info

- Language: Pine Script v5
- Platform: TradingView
- Version: 1.0
- Author: [Rao Aksee Nasir]

---

## 🧠 License & Attribution

Free to use for educational or personal trading purposes. Credit appreciated for forks or modifications.

---

## 📬 Feedback

Questions or improvements? 
