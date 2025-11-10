Stock Market Exploratory Data Analysis (2018 – 2024)

Overview
This project explores the stock market performance of four leading technology companies — Apple (AAPL), Tesla (TSLA), Amazon (AMZN), and Microsoft (MSFT) — between 2018 and 2024.
It focuses on Exploratory Data Analysis (EDA) to uncover meaningful patterns and relationships in the stock data.

Project Objectives
The analysis in this stage (Step 2 of EDA) focuses on:
Importing and inspecting real-world stock data
Handling missing values and checking dataset structure
Visualizing stock price trends over time
Calculating daily returns for each company
Measuring correlation between different stocks

Dataset Details
The dataset, tech_stocks_2018_2024.csv, was generated using Python’s yfinance library.
Each record includes:
Column	Description
Date	Trading date
Open, High, Low, Close, Adj Close	Stock prices for the day
Volume	Number of shares traded
Company	Company ticker name

Time period: 2018 – 2024

Key Insights
All four stocks show strong growth trends during the analysis period.
Apple and Microsoft display a high positive correlation, suggesting similar market movements.
Tesla exhibits higher volatility compared to others.
Daily returns highlight short-term fluctuations and help assess risk levels.

How to Use

Run the Jupyter Notebook stock_market_EDA.ipynb to reproduce the analysis.
Install dependencies with:
pip install pandas numpy matplotlib seaborn yfinance

Tools & Libraries
Python
pandas, numpy – data manipulation
matplotlib, seaborn – visualization
yfinance – data collection