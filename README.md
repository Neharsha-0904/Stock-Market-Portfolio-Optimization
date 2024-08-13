# Stock Analysis Project 📈📊

Welcome to the Stock Analysis Project! This project focuses on analyzing and visualizing stock data for several major companies to understand their performance and optimize investment strategies.

## Project Overview 🎯

This project involves retrieving stock data for selected companies, visualizing key metrics, and evaluating portfolio performance. The aim is to analyze stock trends, calculate moving averages, and identify the optimal asset allocation to maximize returns.

## Dataset Description 📈

The dataset used in this project includes stock prices and trading volumes for the following tickers:

- **RELIANCE.NS**: Reliance Industries Limited
- **TCS.NS**: Tata Consultancy Services Limited
- **INFY.NS**: Infosys Limited
- **HDFCBANK.NS**: HDFC Bank Limited

The data spans the past year and includes daily records of:

- **Open Price**: The price at which the stock opened.
- **High Price**: The highest price during the day.
- **Low Price**: The lowest price during the day.
- **Close Price**: The price at which the stock closed.
- **Volume**: The number of shares traded.

## Approach 🛠️

### Data Retrieval and Transformation 📥

1. **Data Download**: Stock data is retrieved using the `yfinance` library.
2. **Data Transformation**: The data is reshaped to facilitate analysis, including pivoting to format data for visualization.

### Data Visualization 📉

- **Adjusted Close Prices Over Time**:
  This plot shows the adjusted close price of each stock over time.

- **Moving Averages and Trading Volumes**:
  Visualize 50-day and 200-day moving averages alongside trading volumes for each stock.

- **Distribution of Daily Returns**:
  A histogram displaying the distribution of daily returns for each stock.

- **Correlation Matrix of Daily Returns**:
  A heatmap showing the correlation between daily returns of different stocks.

### Portfolio Optimization 💡

1. **Calculate Expected Returns and Volatility**:
   - Expected returns and volatility are computed to understand the performance of each stock.

2. **Simulate Portfolios**:
   - Random portfolios are generated to find the efficient frontier and identify the optimal portfolio with the highest Sharpe ratio.

   A scatter plot illustrating the efficient frontier with the Sharpe ratio as the color gradient.

3. **Optimal Portfolio Allocation**:
   - The portfolio with the maximum Sharpe ratio is identified and its weights are provided.

   The allocation of assets in the optimal portfolio.

## Files and Code Structure 📁

- `stock_data_analysis.py`: Main script for downloading, transforming, and analyzing stock data.
- `visualizations.py`: Code for generating various visualizations.
- `portfolio_optimization.py`: Code for simulating portfolios and calculating optimal asset allocation.

## Installation and Requirements 🛠️

Ensure you have the following packages installed:

- `pandas`
- `numpy`
- `yfinance`
- `matplotlib`
- `seaborn`

You can install them using pip:

```bash
pip install pandas numpy yfinance matplotlib seaborn
```

## Usage 🚀

1. **Run Analysis**: Execute `stock_data_analysis.py` to download and preprocess data.
2. **Generate Visualizations**: Use `visualizations.py` to create plots and visualizations.
3. **Optimize Portfolio**: Run `portfolio_optimization.py` to simulate portfolios and find the optimal allocation.

## Conclusion 🎉

The Stock Analysis Project provides insights into stock performance and aids in portfolio optimization. By analyzing historical stock data and calculating key metrics, we strive to enhance investment strategies and optimize returns.

For further details or questions, feel free to reach out!

---

Neharsha Vishnu Kanneganti
