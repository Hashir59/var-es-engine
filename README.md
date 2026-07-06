# Portfolio Risk Engine

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Hashir59/portfolio-risk-engine/blob/main/Portfolio_Risk_Engine.ipynb)


A Python-based portfolio market risk engine that estimates portfolio risk using multiple industry-standard methodologies.

## Features

- Historical Simulation Value-at-Risk (VaR)
- Parametric (Variance-Covariance) VaR
- Monte Carlo Simulation
- Expected Shortfall (CVaR)
- Kupiec Proportion-of-Failures Backtesting
- Risk visualizations

## Technologies

- Python
- NumPy
- Pandas
- SciPy
- Matplotlib

## Project Overview

This project was developed to explore quantitative risk management techniques used in investment banking and asset management. It estimates portfolio downside risk using multiple VaR methodologies, validates model performance through statistical backtesting, and generates visual reports.

## How to Run

Open the notebook locally using Jupyter Notebook or click the **Open in Colab** badge above.

## Future Improvements

- GARCH volatility models
- Portfolio optimization
- Interactive dashboard
- Additional backtesting methods
- Component/Incremental VaR for per-position risk attribution.
- Christoffersen independence test to detect breach clustering (not just frequency).
- Interactive `ipywidgets` dashboard for live parameter tuning inside Colab.
