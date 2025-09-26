# Tesla Stock Analysis

This repository contains a Python project analyzing Tesla's historical stock data. The objective is to compute daily returns, apply a 50-day moving average (SMA50), visualize stock price trends, and calculate basic risk/return statistics.

---

## Overview
- **Dataset**: `Tesla_stock_price.csv`
- **Technologies**: Python, Pandas, Matplotlib, Jupyter Notebook
- **Key Features**:
  - Data loading and cleaning
  - Calculation of daily returns
  - Implementation of a 50-day Simple Moving Average (SMA50)
  - Visualizations of price trends and volatility
  - Computation of average daily return and volatility (standard deviation of returns)

---

## Example Outputs
- Stock price with SMA50 overlay
- Daily returns plot
- Summary statistics:
  - Average daily return
  - Volatility (risk measure)

---

## Installation and Requirements
Clone the repository and install the dependencies:
```bash
git clone https://github.com/<USERNAME>/Tesla-Stock-Analysis.git
cd Tesla-Stock-Analysis
pip install -r requirements.txt
```

---

## Usage
1. Place the dataset `Tesla_stock_price.csv` in the project directory.
2. Open the Jupyter Notebook:
   ```bash
   jupyter notebook Tesla_stock_analysis.ipynb
   ```
3. Run all cells to generate plots and statistics.

Alternatively, the notebook can be opened directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<USERNAME>/Tesla-Stock-Analysis/blob/main/Tesla_stock_analysis.ipynb)

---

## Next Steps
- Extend the analysis to other stocks or indices (e.g., Apple, S&P500).
- Add additional technical indicators (EMA, Bollinger Bands, RSI).
- Implement and backtest simple trading strategies (e.g., moving average crossover).
