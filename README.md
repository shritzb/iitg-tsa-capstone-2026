# Capstone Project — Time Series Analysis and Stock Market Forecasting

## Live Dashboard
🔗 [View Dashboard](https://shritzb.github.io/iitg-tsa-capstone-2026)

## Overview

This project was developed as part of a Time Series Analysis (TSA) capstone focused on stock market forecasting, volatility analysis, and portfolio construction using Python. The objective was to apply statistical forecasting techniques to real financial market data, evaluate prediction performance, and execute a live virtual portfolio using StockGro.

The project combines forecasting models, volatility estimation, trend analysis, correlation-based diversification, and practical portfolio allocation strategies to simulate real-world financial decision-making.

---

# Project Objectives

* Analyze historical stock market data
* Perform preprocessing and stationarity testing
* Build time series forecasting models
* Predict short-term stock prices
* Evaluate model accuracy using statistical metrics
* Analyze volatility and market trends
* Construct a diversified investment portfolio
* Execute and monitor a live virtual portfolio on StockGro
* Compare predicted vs actual market performance

---

# Selected Stocks

The following NSE-listed stocks were selected for analysis:

* Tata Consultancy Services (TCS)
* HDFC Bank
* Hindustan Unilever
* Sun Pharmaceuticals
* Mahindra & Mahindra

Additional candidate stocks were screened during the volatility analysis phase.

---

# Methodology

## 1. Data Collection

Historical stock price data was collected using the yFinance API.

## 2. Data Preprocessing

* Missing value handling
* Closing price extraction
* Log return computation
* Stationarity testing using the Augmented Dickey-Fuller (ADF) Test

## 3. Forecasting Models

The project primarily implemented the ARIMA forecasting model for short-term stock price prediction.

Forecasts were evaluated using:

* RMSE (Root Mean Squared Error)
* MAPE (Mean Absolute Percentage Error)
* Directional Accuracy

## 4. Volatility and Trend Analysis

* Rolling standard deviation of log returns
* Correlation matrix analysis
* STL decomposition for trend, seasonality, and residual analysis

## 5. Portfolio Construction

Portfolio allocation was based on:

* Forecast-guided allocation
* Volatility-aware sizing
* Correlation-based diversification

A virtual capital of ₹10,00,000 was allocated across selected stocks.

## 6. Live Portfolio Execution

The portfolio was executed using the StockGro virtual trading platform and monitored over the selected trading window.

---

# Tools and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* yFinance
* Google Colab
* StockGro

---

# Key Features

* Time series forecasting using ARIMA
* Forecast evaluation metrics
* Volatility estimation
* Correlation heatmap visualization
* STL decomposition
* Portfolio allocation analysis
* Predicted vs actual market comparison
* Interactive dashboard visualizations

---

# Results and Findings

* ARIMA demonstrated moderate forecasting capability for relatively stable stocks.
* Volatility-aware diversification improved overall portfolio stability.
* Real market behavior highlighted the limitations of short-term forecasting models.
* The live execution phase demonstrated how statistical forecasting and portfolio management interact under dynamic market conditions.

---

# Limitations

* Forecasting relied primarily on historical price data.
* External macroeconomic and news-based factors were not incorporated.
* Only classical statistical forecasting methods were experimentally implemented.
* Short forecasting windows limit predictive reliability in highly volatile markets.

---

# Repository Contents

| File | Description |
|------|-------------|
| `README.md` | Project documentation |
| `TSA_Capstone_Main.ipynb` | Full pipeline notebook |
| `TSA_Capstone_Report_Final.pdf` | 10-page project report |
| `index.html` | Interactive portfolio dashboard |

---

# Future Improvements

* Implementation of LSTM and deep learning-based forecasting models
* Sentiment analysis integration using financial news
* Real-time market data pipelines
* Enhanced portfolio optimization techniques

---

# Author
Shritama Bandyopadhyay

## Pipeline
Data Fetching → Preprocessing → ARIMA Forecasting → Volatility Analysis → Portfolio Construction → Live Trading → Evaluation
