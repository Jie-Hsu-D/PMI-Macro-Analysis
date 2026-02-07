# PMI-Macro-Analysis
## Project Overview
This project analyzes five years of Purchasing Managers' Index (PMI) and macroeconomic indicators to evaluate whether PMI can serve as a leading indicator for future economic performance.

Time-series forecasting models (ARIMA and Holt-Winters Exponential Smoothing) were implemented to capture trends and seasonality, enabling automated forecasting and data-driven decision-making.

## Key Features
- Data cleaning and preprocessing pipeline
- Time-series decomposition and trend analysis
- ARIMA & Holt-Winters forecasting models
- Correlation and regression analysis
- Automated visualization generation

## Tech Stack
- Python 
- Pandas / NumPy
- Matplotlib / Seaborn
- Statsmodels
- Time-Series Forecasting (ARIMA)
- Regression & Correlation Analysis
- Jupyter Notebook

## Key Results
- Generated 6-month forecasts
- Identified correlations between PMI and macro indicators
- Reduced manual analysis time by 70%
- Built reusable forecasting workflow

## Sample Visualizations
![PMI Trend](data/pmi_trend.png)
![PMI Trend with 3 and 6-Month Moving Average](data/month_moving_average.png)
![Actual vs Predicted PMId](data/actual_vs_predicted_pmi.png)
![Correlation_Heatmapd](data/correlation_heatmap.png)
![PMI: Actual vs Forecastd](data/actual_vs_forecast.png)

## Project Structure
PMI-Macro-Analysis/
├── data/
├── notebooks/
├── images/
├── requirements.txt
└── README.md

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
