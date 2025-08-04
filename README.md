# Portfolio Optimization with the Black-Litterman Model

This project implements the **Black-Litterman portfolio optimization model** in Python using live market data.  
It blends **market-implied returns** with **investor-specific views** to produce realistic, risk-adjusted allocations.

## Features
- Fetches live historical data via Yahoo Finance
- Calculates market-implied returns
- Integrates investor views into return estimates
- Optimizes for maximum Sharpe ratio
- Visualizes efficient frontier and portfolio allocation

## Technologies
- Python, Pandas, NumPy
- Matplotlib for visualization
- yFinance for market data
- PyPortfolioOpt for optimization

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook black_litterman_portfolio.ipynb

