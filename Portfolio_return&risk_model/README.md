# Portfolio Risk & Return Analysis

## Overview
This project implements a portfolio risk and return analysis system using historical ETF price data.
It evaluates how different asset weighting strategies affect portfolio performance by computing expected returns, volatility, and risk-adjusted metrics.

The project is designed as an educational and analytical model, focusing on portfolio behavior rather than real-world trading execution.

---

## Key Features
- Fetches and preprocesses historical market data using yfinance
- Computes daily and annualized returns and volatility
- Implements multiple portfolio weighting strategies:
    - Equal Weighting
    - Inverse Volatility Weighting
    - Sharpe Ratio-based Weighting
- Calculates portfolio risk using covariance matrices
- Performs Monte Carlo simulation to generate random portfolios
- Visualizes risk–return trade-offs and Sharpe ratios
---

## Methodology
1. Download adjusted historical price data
2. Compute daily percentage returns
3. Annualize returns and volatility
4. Apply different weighting strategies
5. Compute portfolio-level metrics:
    - Expected Return
    - Volatility
    - Sharpe Ratio
6. Generate random portfolios using Monte Carlo simulation
7. Visualize portfolio performance in risk–return space

---

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- yFinance

---

## Results & Visualizations
The project produces :
1. Annualized portfolio return and volatility
2. Risk-adjusted performance metrics
3. A Monte Carlo scatter plot showing:
    - Risk vs Return of random portfolios
    - Sharpe ratio color mapping
    - Highlighted selected portfolio

These visualizations help analyze how asset allocation impacts overall portfolio risk.

---

## Notes
- This project is intended for learning and experimentation only.
- It does not represent a live trading system or financial advice.

---

## How to Run

1. Clone the repository
2. Install dependencies:
    - pip install pandas numpy matplotlib yfinance
3. Run the notebook to:
    - Fetch data
    - Compute metrics
    - Generate plots