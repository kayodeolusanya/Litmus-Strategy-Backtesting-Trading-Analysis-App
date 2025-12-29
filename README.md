# Litmus-Strategy-Backtesting-Trading-Analysis-App

Litmus is an interactive financial strategy backtesting application built to evaluate trading strategies using historical market data. It enables users to test, analyze, and visualize strategy performance using real-world stock data through an intuitive Streamlit interface.


## 🚀 Key Features

* **Strategy Backtesting Engine**

  * Built on the **Backtrader** framework for robust and extensible strategy testing
  * Implements technical strategies such as Simple Moving Average (SMA) Crossover
  * Supports long-position trade execution and signal-based entries/exits

* **Live Market Data Integration**

  * Fetches historical stock price data using Yahoo Finance (yfinance)
  * Supports multiple equities (e.g., AAPL, MSFT, GOOG)
  * Configurable date ranges for flexible analysis

* **Interactive Web Interface**

  * Developed using **Streamlit** for fast and responsive UI
  * User-controlled inputs for:

    * Ticker selection
    * Strategy parameters
    * Date ranges
  * Session-based persistence for smoother user experience

* **Performance Visualization**

  * Plots portfolio value and price movements
  * Visualizes strategy execution over time
  * Supports Matplotlib-based charting

* **Data Cleaning & Validation**

  * Standardized OHLCV column handling
  * Automated missing data cleanup
  * Defensive checks to ensure backtesting integrity


## 🧠 Strategy Example

**SMA Crossover Strategy**

* Buys when the short-term moving average crosses above the long-term moving average
* Exits when the crossover reverses
* Demonstrates trend-following behavior and signal-based execution


## 🛠️ Tech Stack

* **Python**
* **Backtrader** – Backtesting framework
* **Streamlit** – Interactive web app
* **yFinance** – Market data sourcing
* **Pandas / NumPy** – Data processing
* **Matplotlib** – Visualization



## 🎯 Use Cases

* Trading strategy experimentation
* Financial data analysis
* Algorithmic trading prototyping
* Academic or personal research
* Portfolio performance evaluation


## 🔮 Future Enhancements

* Multiple strategy selection (RSI, MACD, Bollinger Bands)
* Short-selling and position sizing
* Risk metrics (Sharpe, Drawdown, Volatility)
* Strategy comparison dashboards
* Exportable performance reports


## 🧪 Disclaimer

This project is for **educational and research purposes only** and does not constitute financial advice.
