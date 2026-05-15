# Correlation and Covariance Analysis

## Overview
This project analyzes the correlation and covariance between historical stock data over the past 5 years for Apple, Microsoft, JP Morgan, Coca-Cola, and Exxon Mobil using Python, Pandas, Matplotlib, Seaborn, and yfinance.

The goal was to evaluate: Inter-asset relationships and analyse diversification and risk potential through examination of covariance and correlation 
- Covariance

---

## Dataset
Historical stock data was downloaded using yfinance.

Tickers used:
- AAPL
- MSFT
- JPM
- KO
- XOM

Time period:
- 17th May, 2021 to 14th May, 2026

---

## Methods Used
- Data cleaning
- `pct_change()` - daily returns
- `describe()` - analysis on returns
- `corr()` - correlation between assets
- `cov()` - covariance between assets
- `cumsum()` - cumulative return trends
- visualization of cumulative returns using Matplotlib
- heatmap of covariance and correlation using Seaborn

---

## Key Metrics Analyzed
- percentage change in asset prices over the past 5 years
- mean returns
- volatility/standard deviation
- correlation
- covariance
- cumulative returns

---

## Visualizations
This project includes:
- cumulative returns chart
- covariance heatmap
- correlation heatmap

---

## Key Insights
- all assets grew over the 5 years, with Coca-Cola seeing the least growth and Exxon Mobil showing the strongest growth in returns
- Apple's returns were the most volatile with a standard deviation of 0.017295, whereas Coca-Cola's returns were the most stable with a standard deviation of 0.010049
- Apple and Microsoft are the most closely related, showing the effect of the businesses being in the same market
- Microsoft and Exxon Mobil were the least related, suggesting diversification potential to reduce portfolio risk.


---

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- yfinance
- Jupyter Notebook
