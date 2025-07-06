# VaR_Montecarlo
This project implements a Monte Carlo simulation approach to estimate the **Value at Risk (VaR)** of a simple financial portfolio. 

The goal is to simulate future price paths for one or more assets using historical data, and then use those simulations to compute the empirical distribution of portfolio returns.

---

## 🧮 Methods and Tools

- **Monte Carlo Simulation** to generate future asset price paths.
- **Geometric Brownian Motion** model as the price evolution assumption.
- **Python** libraries used:
  - `pandas` for data handling
  - `numpy` for numerical operations
  - `matplotlib` for data visualization
  - `yfinance` for data acquisition
