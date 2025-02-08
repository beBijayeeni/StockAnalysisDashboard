# Stock Analysis Dashboard

This project fetches stock price data from Yahoo Finance using `yfinance` and provides various analyses such as daily stock prices, monthly reports, and interactive candlestick charts using Plotly. It also saves the reports to an Excel file.

## Features

- **Daily Stock Prices:** Retrieve and display opening, high, low, and closing prices.
- **Option Reports:** Generate reports (e.g., for a 1-month period) showing the highest and lowest prices.
- **Interactive Charts:** Visualize stock data with interactive candlestick charts.
- **Data Persistence:** Save report data to an Excel file for future reference.

## Project Structure

StockAnalysisDashboard/
├── README.md #Project overview 
├── requirements.txt #Lists all required Python libraries.
├── stock_analysis.py #Contains functions for saving stock report data to an Excel file as well as functions to fetch daily stock prices, generate option reports, and plot interactive candlestick charts.
└── stock_reports.xlsx #Stores ouput file
