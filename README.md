# Portfolio Risk Assessment under Extreme Market Conditions: VaR, ES and Backtesting

## Overview

This project develops a quantitative market risk framework for Vietnamese equities using Value at Risk (VaR) and Expected Shortfall (ES). The model evaluates portfolio downside risk under extreme market conditions and validates its forecasting performance through statistical backtesting.

## Methodology

- Historical Simulation VaR (99%)
- Expected Shortfall (CVaR)
- Rolling-window backtesting
- Kupiec Unconditional Coverage Test
- Christoffersen Conditional Coverage Test

## Results

- Historical VaR (99%): VND 142.30 million
- Expected Shortfall: VND 186.45 million
- Kupiec UC Test: p = 0.816
- Christoffersen Test: p = 0.737

## Tech Stack

Python, NumPy, Pandas, SciPy, Matplotlib

## Repository Structure

```
.
├── var_es_backtesting.ipynb
├── Report_.pdf
└── README.md
```
