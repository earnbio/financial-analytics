# Personal Finance Dashboard

An interactive personal finance analytics project built in Python and Power BI to explore spending patterns, cash flow trends, and future forecasted cash flow.

## Project Overview

This project analyzes personal transaction data to understand income, expenses, and monthly net cash flow. It also includes an ARIMA-based forecast to estimate future cash flow trends.

## Dataset

The data used in this project comes from Kaggle:  
[Personal Finance Dataset](https://www.kaggle.com/datasets/entrepreneurlife/personal-finance?select=personal_transactions_dashboard_ready+%282%29.xlsx) [web:569]

## Tools Used

- Python
- Pandas
- Matplotlib / Plotly
- Statsmodels
- Power BI
- Excel

## Project Goals

- Clean and prepare personal transaction data
- Analyze income, expenses, and net cash flow
- Build a monthly cash flow dashboard
- Forecast future cash flow using ARIMA
- Present insights in an interactive Power BI report

## Key Insights

- Monthly cash flow trends were analyzed over time
- Forecasting was used to estimate future net cash flow
- Visuals highlight historical performance and expected future movement
- Categories and time periods were used to understand spending behavior

## Dashboard Preview

[Dashboard Preview](output/powerbi_dashboard.pdf)

## Forecasting Approach

An ARIMA model was used to forecast future net cash flow based on historical monthly trends.  
This helped estimate short-term future values and confidence intervals.

## Files in This Project

- `data/` — raw and cleaned datasets
- `notebook/` — Jupyter notebooks used for analysis
- `output/` — exported charts, dashboard 

## How to View

1. Open the Power BI report or PDF in the `output/` folder
2. Review the notebook for the cleaning and forecasting steps
3. Explore the dashboard screenshot and forecast chart

## Author

Chunya Chongkavinit
