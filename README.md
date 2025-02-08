# Stock Analysis Dashboard

This project fetches stock price data from Yahoo Finance using `yfinance` and provides various analyses such as daily stock prices, monthly reports, and interactive candlestick charts using Plotly. It also saves the reports to an Excel file.

## Features

- **Daily Stock Prices:** Retrieve and display opening, high, low, and closing prices.
- **Option Reports:** Generate reports (e.g., for a 1-month period) showing the highest and lowest prices.
- **Interactive Charts:** Visualize stock data with interactive candlestick charts.
- **Data Persistence:** Save report data to an Excel file for future reference.

## Project Structure

```sh
StockAnalysisDashboard/
├── README.md #Project overview and usage instructions.
├── requirements.txt #Lists all required Python libraries.
├── stock_analysis.py #Contains functions for saving stock report data to an Excel file as well as functions to fetch daily stock prices, generate option reports, and plot interactive candlestick charts.
└── stock_reports.xlsx #Stores output file

```


## Installation

### Clone the repository

```bash
git clone <repository-url>
cd StockAnalysisDashboard
```

### Install Dependencies
```sh
pip install -r requirements.txt
```

## Usage

Run the main script:
```sh
python stock_analysis.ipynb
```
This will:

- Launch the Dashboard: Run the application to access the web-based interface for stock analysis.

- Select Companies: Use the search or dropdown feature to choose specific NSE & BSE listed companies for detailed analysis.

- Generate Reports and Visualizations: View comprehensive reports and various chart types to analyze the selected company's stock performance.

## Running the Project

**Set up your environment:**  
Install Python 3 and then run:
```bash
pip install -r requirements.txt
```
