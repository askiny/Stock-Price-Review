# Stock-Price-Review

In this project, I examined the stock prices of Alphabet (Google), Meta Facebook), Cisco, Intel, AMD, Qualcomm, Apple, Samsung, Xiaomi, and Tesla using Yahoo-Finance data.

# Project Subjects

Change Column: For a company, it is indicated as 1 if that day's closing price is 2.5% higher than the opening price, -1 if it is lower than 2.5%, and 0 if it does not exceed the threshold value.

Difference Column: For a company, it is expressed as 1 if the day's opening price is 2.5% higher than the previous day's opening price, -1 if it is lower than 2.5%, and 0 if it does not exceed the threshold value.

Longest Intervals: These are the columns that show the longest increasing and decreasing intervals for both Change and Difference columns.

# Libraries Used

- Data Source: yfinance
- Data Proccesing: Pandas
