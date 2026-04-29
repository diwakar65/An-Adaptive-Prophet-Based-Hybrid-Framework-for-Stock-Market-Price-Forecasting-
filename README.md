# An-Adaptive-Prophet-Based-Hybrid-Framework-for-Stock-Market-Price-Forecasting-
An advanced stock market forecasting and portfolio optimization system using a Prophet-LSTM hybrid framework with volatility-aware modeling, technical analysis, risk management, and Monte Carlo simulation. This project improves stock price prediction accuracy and helps investors make better portfolio decisions through adaptive forecasting .
Adaptive Prophet-Based Hybrid Framework for Stock Market Forecasting and Portfolio Optimization.
This project presents an advanced stock market forecasting and portfolio optimization system using a Prophet-LSTM hybrid framework. The system combines technical analysis, volatility-aware forecasting, risk analysis, and Monte Carlo-based portfolio optimization to improve stock price prediction accuracy and investment decision-making.

The project is based on the research paper:

“An Adaptive Prophet-Based Hybrid Framework for Volatility-Aware Trend and Seasonality Modeling in Stock Market Price Forecasting”

It integrates forecasting, technical indicators, and portfolio optimization into a single intelligent financial analysis system.

---

Project Objective

The main objective of this project is to predict future stock prices accurately and help investors make better investment decisions by using:

- Technical Analysis
- Prophet Forecasting
- LSTM Hybrid Prediction
- ATR-Based Volatility Detection
- Risk Management Metrics
- Portfolio Optimization using Monte Carlo Simulation

---

Features

✔ Technical Analysis using SMA, RSI, and Candlestick Charts

✔ Prophet-Based Future Price Forecasting

✔ Hybrid Prophet + LSTM Residual Correction Model

✔ Adaptive Bayesian Changepoint Scheduler

✔ ATR-Based Volatility Regime Switching

✔ Profit Estimation and Return Analysis

✔ Portfolio Risk Metrics Calculation

✔ Sharpe Ratio, Sortino Ratio, Maximum Drawdown, and Value at Risk (VaR)

✔ Monte Carlo Portfolio Optimization

✔ Efficient Frontier Visualization

✔ Multi-Stock Comparative Performance Analysis

---

Technologies Used

- Python
- Streamlit
- Facebook Prophet
- TensorFlow / LSTM
- yFinance
- Pandas
- NumPy
- Plotly
- Matplotlib
- Scikit-learn

---

Dataset Source

The project uses live historical stock market data fetched dynamically using Yahoo Finance API ("yfinance") for stocks such as:

- AAPL
- AMZN
- GOOG
- MSFT

Time Period

2014 – 2024

Features Used

- Open
- High
- Low
- Close
- Adjusted Close
- Volume

No static CSV dataset is used. Data is fetched dynamically through API-based integration.

---

Hybrid Forecasting Method

Step 1: Prophet predicts the main stock trend and seasonality.

Step 2: Residual error is calculated:

Residual = Actual Price − Prophet Forecast

Step 3: LSTM learns nonlinear residual patterns.

Final Prediction:

Hybrid Forecast = Prophet Forecast + LSTM Residual Correction

This improves forecasting accuracy over traditional standalone models.

---

Portfolio Optimization

The project performs portfolio optimization using Monte Carlo Simulation to identify:

- Maximum Sharpe Ratio Portfolio
- Minimum Volatility Portfolio
- Efficient Frontier

This helps investors choose better asset allocation strategies.

---

Research Contribution

This work introduces:

- Adaptive Bayesian Changepoint Scheduler
- ATR-Based Volatility Regime Switching
- LSTM Residual Correction Layer

These improvements help outperform:

- ARIMA
- Vanilla Prophet
- LSTM
- GRU

with better RMSE, MAPE, and R² Score.

---

Files Included

- Source Code ("app.py", "app1.py")
- Project Report PDF
- Research Paper PDF
- Requirements File
- Screenshots
- Presentation PPT (if available)

---

How to Run the Project

1. Install required libraries

pip install -r requirements.txt

2. Run the Streamlit application

streamlit run app.py

or

streamlit run app1.py

---

Project Output

The system helps investors understand:

- Which stock to buy
- When to buy
- Future expected stock price
- Portfolio risk level
- Best portfolio allocation
- Expected profit and return

This makes the project useful for real-world financial decision-making.

---

Conclusion

This project combines forecasting, volatility awareness, interpretability, and portfolio optimization into a complete stock market intelligence system. It is designed as a research-based final year major project with practical real-world applications in financial analytics and investment management.

---

Author
D. Diwakar, P. Akhila, B. Divya Sree
CSE (Data Science)
RGMCET, Nandyal
