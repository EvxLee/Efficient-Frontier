# Efficient Frontier: Stock Time-Series Analysis & Portfolio Risk Modeling 
This project focuses on applying data science and machine learning techniques to financial market analysis using stock data from Yahoo Finance. It covers a wide range of topics including data preprocessing, exploratory data analysis, technical indicators, trading strategy design, backtesting, portfolio optimization, and predictive modeling.

The project explores moving averages, technical indicators, and trading strategies such as Moving Average Crossover and Mean Reversion. It incorporates machine learning models to forecast stock returns, evaluates their performance using multiple metrics, and visualizes the results. Additionally, it introduces core financial models such as the Capital Asset Pricing Model (CAPM) and the Efficient Frontier.

## Quick start
- Open the notebook: `Stock Analysis Project.ipynb`.
- Run the cells top to bottom in Jupyter, VS Code, or Google Colab.

## Play with different timeframes
In the notebook, look for variables like `start_date`, `end_date`, or `period`. You can:
- Set explicit ranges, e.g. `start_date = '2018-01-01'`, `end_date = '2023-12-31'`.
- Use a rolling window size for indicators, e.g. change `window = 20` to `50`.
- Switch Yahoo Finance periods, e.g. `period = '1y'`, `period = '5y'`, or `period = 'max'`.


## Play with different stocks
Search for the `ticker` or `tickers` variables in the notebook and replace the symbols with your own. Common spots include:
- `ticker = 'NVDA'` for single-stock examples
- `tickers = ['TSLA', 'MSFT', 'GS', '^GSPC']` for multi-stock and market comparisons

Tip: `^GSPC` is the S&P 500 index. Keep it if a cell compares stocks vs. the market.

## Requirements
- Python 3.x
- Libraries: `yfinance`, `pandas`, `numpy`, `matplotlib`, `statsmodels`, `scikit-learn`

Install example:
```bash
pip install yfinance pandas numpy matplotlib statsmodels scikit-learn
```
