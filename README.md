# Financial Data Analysis with yfinance

This project focuses on analyzing financial datasets using the `yfinance` library to gain insights into market trends and investment opportunities. It involves data cleaning, exploratory data analysis, and visualization techniques.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Data Cleaning](#data-cleaning)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Statistics](#statistics)
- [Credits](#credits)

## Introduction

This project aims to provide a comprehensive analysis of historical stock data for a given stock ticker symbol using the `yfinance` library in Python. The data analysis process involves data cleaning, computation of additional features, exploratory data analysis, and statistical calculations. The insights gained from this analysis can help investors make informed decisions and understand the stock's performance and risk characteristics.

## Installation

1. Clone the repository:

  git clone https://github.com/MorEnergy/Financial_data_analysis.git

2. Install the required dependencies:

  pip install yfinance pandas numpy matplotlib seaborn

## Usage

1. Define the stock ticker symbol and the desired date range in the analyze_financial_data.py script:

  ticker = 'AAPL'
  start_date = '2010-01-01'
  end_date = '2021-12-31'

2. Execute the script to perform data analysis and generate visualizations:

  python analyze_financial_data.py

3. Review the generated plots and the printed statistics for insights into the stock's performance and risk characteristics.

## Data Cleaning
The historical stock data retrieved using yf.download() contains various columns, but we will keep only the relevant ones: 'Open', 'High', 'Low', 'Close', and 'Volume'. Any missing values will be removed to ensure data quality.

## Exploratory Data Analysis
We will create subplots to visualize the stock's closing prices over time and the distribution of daily returns. The histogram with the kernel density estimate will help us understand the distribution of returns, providing insights into the stock's behavior.

## Statistics
We will calculate additional features, including daily returns, log returns, and annualized volatility. The log returns help to stabilize the variance of the returns, and the annualized volatility provides a measure of the stock's risk.

Finally, we will compute basic statistics such as the mean daily return, standard deviation of daily return, annualized return, and the latest annualized volatility.

## Credits

I would love to connect with fellow enthusiasts and professionals in the data, finance, and technology space. Feel free to reach out to me through the following channels:

- Email: [a_raji@outlook.com](mailto:a_raji@outlook.com)
- LinkedIn: [Him](https://www.linkedin.com/in/adam-raji-/)

Let's learn and grow together in this exciting journey of data, finance, and technology!
