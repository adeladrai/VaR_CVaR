# Value at Risk (VaR) & Conditional Value at Risk (CVaR)

This repository contains a Jupyter notebook that demonstrates three commonly used methods to estimate **Value at Risk (VaR)** and **Conditional Value at Risk (CVaR)** for a simple stock portfolio:
1. **Historical Method**  
2. **Parametric (Variance-Covariance) Method**  
3. **Monte Carlo Simulation**  

The notebook uses publicly available data from [Yahoo Finance](https://finance.yahoo.com/) for four sample tech stocks (AAPL, META, NVDA, AMZN) over the period from **January 1, 2021** to **January 1, 2025**. It illustrates how to:
- Fetch and clean historical adjusted closing price data
- Calculate percentage returns
- Compute and visualize VaR & CVaR under different approaches
- Compare the theoretical assumptions and results from each method

---

## Table of Contents
1. [Getting Started](#getting-started)
2. [Dependencies](#dependencies)
3. [Project Structure](#project-structure)
4. [Key Sections of the Notebook](#key-sections-of-the-notebook)
    - [Data Collection](#data-collection)
    - [Historical Method](#historical-method)
    - [Parametric (Variance-Covariance) Method](#parametric-variance-covariance-method)
    - [Monte Carlo Simulation](#monte-carlo-simulation)
5. [Results Overview](#results-overview)
6. [Usage](#usage)
7. [License](#license)

---

## Getting Started

1. **Clone** this repository or **download** the notebook file (`.ipynb`).
2. **Install** the required dependencies (see [Dependencies](#dependencies) section).
3. **Open** the notebook in Jupyter Lab/Notebook (or in any environment that supports `.ipynb` files).
4. **Run** each cell sequentially to replicate the results.

---

## Dependencies

The notebook uses the following Python libraries:

- **Python 3.7+** (recommended)
- [NumPy](https://numpy.org/)
- [pandas](https://pandas.pydata.org/)
- [matplotlib](https://matplotlib.org/)
- [seaborn](https://seaborn.pydata.org/) (used for visualizations)
- [yfinance](https://pypi.org/project/yfinance/) (to fetch stock data)
- [scipy](https://scipy.org/) (for statistical functions, e.g., the normal distribution)

You can install the required libraries using:

```bash
pip install numpy pandas matplotlib seaborn yfinance scipy
