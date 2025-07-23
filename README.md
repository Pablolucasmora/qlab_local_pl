# Options Pricing & Trading Strategies

This repository contains implementations of option pricing models and trading strategy prototypes. The primary goals of the project are:

- **Learn** how to implement different trading indicators and quantitative finance models.
- **Develop** simple trading strategies based on those indicators.
- **Backtest** strategies to understand their behavior (profitability is not the objective yet).

# Options Pricing
**The Options Pricing folder implements the binomial model:**

- **European Options:** No early exercise.

- **American Options:** Allows early exercise decision at each node.

# Trading Strategies
**The Trading Strategies folder contains a frame to test strategies using different indicators and plotting the returns:**

- **Moving Average** (MA)

- **Moving Average Crossovers** (MA_Crossovers)

- **Relative Strength Index** (RSI)

- **Moving Average Convergence Divergence** (MACD)

- **Money Flow Index** (MFI)

Feel free to change any parameters and experiment with your own strategies.

# Installation
**For options pricing:**
- Just execute and introduce the parameters

**For trading:**
- **Clone the repository**
- **Create a virtual environment** (recommended)
- **Install numpy, pandas, matplotlib** and **yfinance**
