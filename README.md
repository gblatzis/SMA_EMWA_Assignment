# SMA and EWMA Volatility Estimation in Python

This Jupyter notebook demonstrates how to estimate financial volatility using Simple Moving Average (SMA) and Exponentially Weighted Moving Average (EWMA) methods. It leverages historical stock price data to compute and visualize volatility.

## Features

- Load historical stock prices using `yfinance`.
- Calculate log returns.
- Estimate volatility using:
  - SMA with different window sizes.
  - EWMA with different lambda decay factors.
- Visualize volatility trends using `matplotlib`.

## Requirements

Install the necessary Python packages using pip:

```bash
pip install pandas numpy matplotlib yfinance
```

Or using a `requirements.txt` file:

```
pandas
numpy
matplotlib
yfinance
```

## How to Use

1. Clone or download this repository.
2. Install dependencies as listed above.
3. Open the notebook:

```bash
jupyter notebook SMA_EMWA.ipynb
```

4. Run the notebook cells sequentially to:
   - Download stock price data.
   - Calculate log returns.
   - Compute SMA and EWMA volatility.
   - Visualize results.

## Example

The notebook includes examples for:
- Calculating SMA volatility for window sizes of 20, 50, and 100 days.
- Calculating EWMA volatility with lambda values 0.99, 0.97, and 0.90.
- Plotting all volatility estimates on a single chart.

## Notes

- The notebook uses daily stock prices.
- Annualized volatility is calculated assuming 252 trading days per year.
