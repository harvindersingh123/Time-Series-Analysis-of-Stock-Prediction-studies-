# Time-Series-Analysis-of-Stock-Prediction-studies
# Stock Prediction - Time Series Analysis

## Overview
This project explores time series analysis techniques for stock price prediction. By examining historical data for selected stocks, we aim to understand trends, patterns, and relationships within the data to provide insights into stock behavior.

---

## Objectives
1. Access and analyze historical stock data.
2. Resample and preprocess the data to focus on monthly adjusted close prices.
3. Perform autocorrelation analysis to identify patterns and dependencies in the stock prices.

---

## Steps Involved
1. **Environment Setup and Data Retrieval**:
   - Configure the environment to access financial data sources.
   - Download the **adjusted close prices** for the following stocks: **FB (Meta Platforms), MMM (3M), IBM, and AMZN (Amazon)** for the past 60 months.

2. **Data Preprocessing**:
   - Resample the data to extract prices for the end of each **business month**.
   - Focus specifically on the **Adjusted Close** values.

3. **Autocorrelation Analysis**:
   - Use the `pandas` library's `autocorrelation_plot()` function to visualize the autocorrelation of monthly adjusted close prices for each stock.
   - Analyze these plots to detect time-dependent relationships.

---

## Tools and Libraries
- **Python**
- **Pandas** for data manipulation
- **Matplotlib** for visualization

---

## Results
The analysis provides:
- A cleaned and resampled dataset of monthly adjusted close prices.
- Autocorrelation plots for each stock, highlighting time series dependencies and insights into stock behavior.

---


