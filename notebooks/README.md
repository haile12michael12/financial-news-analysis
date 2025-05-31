# 📊 Task 2: Quantitative Analysis using PyNance and TA-Lib

## 📝 Objective
In this task, we perform quantitative analysis on historical stock price data using financial indicators. We calculate technical indicators like **Moving Averages**, **RSI**, and **MACD**, and visualize them to interpret stock behavior.

---

## ✅ Tasks Overview

### 1. 📥 Load and Prepare Data
- Use historical stock price data (e.g., AMZN).
- Load into a `pandas` DataFrame.
- Ensure required columns are present: `Open`, `High`, `Low`, `Close`, `Volume`.

### 2. 📉 Apply Analysis Indicators
- **With TA-Lib** *(when available)*:
  - SMA (Simple Moving Averages)
  - RSI (Relative Strength Index)
  - MACD (Moving Average Convergence Divergence)
- **Fallback (Manual Calculation)**:
  - Calculate indicators using `pandas` and `numpy` for environments without TA-Lib.

### 3. 📊 Use PyNance for Financial Metrics
- Extract additional financial statistics (e.g., volatility, beta, etc.) using PyNance if applicable.
- Perform time-series exploration of trends and volatility.

### 4. 📈 Visualize Data
- Line charts for Close Price with SMA overlays.
- RSI chart with overbought (70) and oversold (30) levels.
- MACD and Signal Line chart to detect crossovers and divergence patterns.

---

## 🧪 KPIs

| KPI                          | Description                                               |
|-----------------------------|-----------------------------------------------------------|
| 📚 Proactivity to Self-learn | Explored alternate solutions when TA-Lib wasn't available |
| 🎯 Accuracy of Indicators    | Correct formula usage and rolling/EMA logic               |
| 📊 Completeness of Analysis  | Full pipeline: Load → Calculate → Visualize               |

---

## 🚀 Development Instructions

### Git Workflow

1. Merge `task-1` into `main` using a Pull Request.
2. Create a new branch:
 
   git checkout -b task-2
