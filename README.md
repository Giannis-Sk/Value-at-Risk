# Multi-Method Value at Risk (VaR) & Backtesting Engine

A quantitative risk management tool built in Python that calculates and backtests Portfolio Value at Risk (VaR) and Conditional Value at Risk (CVaR) using three distinct methodologies.

## Features
- **Data Fetching:** Pulls historical price data automatically via `yfinance`.
- **Historical Simulation:** Non-parametric approach using historical asset returns.
- **Parametric Method:** Assumes a normal distribution using mean and standard deviation.
- **Monte Carlo Simulation:** Generates random price paths to simulate future portfolio volatility.
- **Visual Backtesting:** Overlays rolling 30-day VaR thresholds on historical returns to identify breaches and exception rates.

## Technologies Used
- Python (`pandas`, `numpy`, `scipy`, `matplotlib`, `yfinance`)

