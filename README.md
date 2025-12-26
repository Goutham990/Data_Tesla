# Tesla Stock Analysis: GBM Simulation & Technical Indicators

This repository contains a Jupyter Notebook designed for the analysis and simulation of Tesla's historical stock data. The project utilizes **Geometric Brownian Motion (GBM)** for stochastic price modeling and incorporates key technical indicators like **RSI** and **MACD** for trend analysis.

##  Project Overview
The goal of this project is to apply financial engineering concepts to real-world stock data. By leveraging Python's data science ecosystem, the notebook provides:
* **Price Prediction**: Simulating future price paths using the GBM model.
* **Momentum Analysis**: Using RSI to find potential reversal points.
* **Trend Identification**: Using MACD to determine the strength and direction of the stock's trend.

##  Key Components

### 1. Geometric Brownian Motion (GBM)
The GBM is a mathematical model used to simulate stock price movement based on historical drift (average return) and volatility. It assumes that stock prices follow a random walk with a consistent trend.

### 2. Relative Strength Index (RSI)
A momentum oscillator that measures the speed and change of price movements. The notebook implements a standard 14-day RSI, highlighting:
* **Overbought:** RSI > 70
* **Oversold:** RSI < 30

### 3. Moving Average Convergence Divergence (MACD)
A trend-following momentum indicator that shows the relationship between two moving averages of a security’s price.
* **MACD Line:** 12-day EMA minus 26-day EMA.
* **Signal Line:** 9-day EMA of the MACD Line.

##  Installation & Setup
To run this analysis locally, ensure you have Python installed, then install the required dependencies:

```bash
pip install pandas numpy matplotlib
