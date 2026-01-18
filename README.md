# Efficinet Frontier Project: Stock Time-Series Analysis & Portfolio Risk Modeling
Exploration of stock market data using Yahoo Finance. It covers basic price analysis and portfolio concepts such as Moving Average Crossover Strategy, CAPM, and efficient frontier.

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
