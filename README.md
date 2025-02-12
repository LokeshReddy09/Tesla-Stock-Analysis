# Tesla-Stock-Analysis

## Overview
This project performs an in-depth analysis of Tesla stock prices, exploring key metrics, technical indicators, and applying time series forecasting models like ARIMA and LSTM. The goal is to understand Tesla’s stock behavior, identify important trends, and forecast future price movements.

## Features
- **Data Collection & Exploration**
  - Load Tesla stock data from a CSV file.
  - Display data overview, check for missing values, and identify duplicates.
- **Data Cleaning & Preprocessing**
  - Convert data types, handle missing values, and ensure data consistency.
- **Exploratory Data Analysis (EDA)**
  - Visualize Tesla's stock price trends over time.
  - Analyze trading volume, daily price ranges, and percentage changes.
  - Generate candlestick charts for market trends.
  - Compute daily returns and assess stock volatility.
  - Investigate correlation between trading volume and stock price.
- **Technical Indicators**
  - Calculate and visualize moving averages (SMA, EMA).
  - Implement Relative Strength Index (RSI) for momentum analysis.
  - Apply Bollinger Bands to assess price volatility.
- **Time Series Forecasting**
  - Use ARIMA for statistical forecasting.
  - Implement LSTM neural networks for deep learning-based forecasting.

## Dependencies
Ensure you have the following Python libraries installed:
```bash
pip install pandas numpy matplotlib seaborn mplfinance statsmodels pmdarima tensorflow keras
```

## Usage
1. **Load Data**: Modify the `df = pd.read_csv("path_to_file.csv", parse_dates=True, index_col='Date')` line to load your dataset.
2. **Run Analysis**: Execute the scripts to generate insights and visualizations.
3. **Forecasting**: Train ARIMA and LSTM models to predict future stock prices.

## Visualizations & Insights
- **Stock Trends**: Identify long-term trends and price movements.
- **Trading Volume**: Understand market activity.
- **Volatility Analysis**: Evaluate stock risk.
- **Momentum Indicators**: Detect potential buy/sell signals.
- **Forecasting**: Predict future price movements using statistical and ML models.

## Future Improvements
- Implement additional forecasting techniques like Prophet.
- Enhance feature engineering with sentiment analysis from financial news.
- Develop a real-time dashboard using Streamlit or Flask.

## Author
**Lokesh Reddy Sontireddy**
