# Project Summary: Yes Bank Stock Closing Price Prediction
Project Summary -
# Introduction
This project aims to analyze Yes Bank's stock performance over time and predict monthly closing prices. The dataset contains historical stock price information, including opening, highest, and lowest prices. A significant focus is to assess how major events, such as the Rana Kapoor fraud case, affected Yes Bank’s stock price. The analysis will employ time series models and machine learning techniques to build predictive models.

# Problem Statement
Yes Bank, a major player in the Indian banking sector, has experienced significant stock price fluctuations over the years. These fluctuations were driven by market conditions, internal financial crises, and regulatory actions.

The objective of this project is to analyze historical stock price data to:

1.Understand stock price trends and their correlations with market movements.

2.Detect anomalies, missing values, and outliers in stock price variations.

3.Evaluate volatility and risk factors using statistical and visual techniques.

4.Provide insights on long-term investment potential for Yes Bank's stock.

# Define Your Business Objective?
The primary business objective is to provide insights into

Yes Bank’s stock price movements

predict future closing prices

This can help investors, financial analysts, and stakeholders make informed decisions based on historical trends and potential risks.

# Dataset Overview:
1.The dataset contains 185 rows and 5 columns: Date, Open, High, Low, and Close prices.
2.No missing values are present and No duplicate values.
3.The Date column is stored as an object (string) and needs to be converted to a date format for time-series analysis.
4.The stock prices are stored as floating-point numbers.

# Variables Description
Column Name	Data Type	Description	Example Value
Date	Object	Month and year of the stock data (in "MMM-YY" format).	Jul-05
Open	Float64	Opening price of Yes Bank stock for the given month.	13.00
High	Float64	Highest price of Yes Bank stock during the month.	14.00
Low	Float64	Lowest price of Yes Bank stock during the month.	11.25
Close	Float64	Closing price of Yes Bank stock for the given month.	12.46

Here we have Date in Object type need to convert into datetime format ,
Making it easier to plot and visualise


# Solution to Business Objective:

What do you suggest the client to achieve Business Objective ?
Explain Briefly.

The goal of Exploratory Data Analysis (EDA) in this project is to uncover trends, patterns, and relationships in Yes Bank’s stock price data. Specifically, EDA aims to:

Understand Stock Price Behavior: Analyze historical stock price movements to identify trends, volatility, and seasonality. Detect Anomalies & Outliers: Identify sudden price fluctuations or inconsistencies in the data. Feature Relationships: Examine correlations between Open, High, Low, and Close prices to determine influential factors. Data Quality Assessment: Check for missing values, inconsistencies, or errors that could impact model accuracy. Visualization for Insights: Use plots (line charts, histograms, box plots, etc.) to visually interpret stock price patterns over time.

# Conclusion

The project successfully analyzed Yes Bank’s stock price trends and built a predictive model for closing prices using machine learning techniques. By performing exploratory data analysis (EDA), handling missing values, selecting appropriate features, and experimenting with multiple models, the study evaluated the effectiveness of different prediction approaches. The results demonstrated the feasibility of using time series models and regression techniques for stock price forecasting, though market volatility and external financial events remain key challenges in predictive accuracy.
