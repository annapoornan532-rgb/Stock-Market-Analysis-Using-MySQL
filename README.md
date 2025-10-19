Stock Market Analysis using MySQL

https://in.pinterest.com/pin/400890804352355059/


Introduction :

This dataset offers a comprehensive collection of historical data for the Nifty index, sourced from Yahoo Finance. The Nifty index, managed by the National Stock Exchange of India (NSE), represents the performance of the top 50 companies listed on the exchange, covering various sectors of the Indian economy. Utilizing Yahoo Finance's extensive database, this dataset spans a significant timeframe, providing insights into the Nifty index's performance over the years. From seasoned investors to budding analysts, this dataset serves as a valuable resource for conducting in-depth analyses, devising trading strategies, and exploring trends within the Indian stock market landscape.

Purpose :

 The purpose of this dataset is to facilitate analysis of historical trends in the Nifty index, testing of trading strategies, and research on stock market behavior.

About data:

 The dataset was obatined from yahoo finance. The dataset contains information of NIFTY index of 1 year(March 2023 to March 2024).This dataset contains 7 columns and 244 rows.

Date[date]: The date of the trading session.

Open[double]: The opening price of the Nifty index for the trading session.

High[double]: The highest price reached by the Nifty index during the trading session.

Low[double]: The lowest price reached by the Nifty index during the trading session.

Close[double]: The closing price of the Nifty index for the trading session.

Adj Close[double]: The adjusted closing price of the Nifty index, accounting for any corporate actions such as dividends or stock splits.

Volume[text]: The total volume of shares traded for the Nifty index during the trading session.

Approach

This project follows a structured approach:

1. Data Import & Cleanliness:

The CSV file is imported into a MySQL database for easy querying.
Data is pre-processed to ensure there are no missing values or inconsistencies.

2. SQL Queries:

Various SQL queries are written to extract key insights from the dataset. These queries address important questions such as the highest opening price, volume analysis, and percentage changes over time.

3. Trend Analysis:

Time-series analysis is conducted to observe the Nifty index's daily, weekly, and monthly behavior.
Questions like average daily trading volume and price range are answered using SQL aggregation functions.

4. Performance Insights:

The project investigates performance metrics, such as the highest volume traded on a single day, the average closing price, and the largest daily price change.
**Questions Solved in this SQL file **:

1.What is the total volume traded on all recorded dates?

2.What is the highest opening price recorded?

3.On which date did the NIFTY index reach its highest value?

4.What is the lowest closing price recorded?

5.On which date did the NIFTY index reach its lowest value?

6.What is the average closing price over the entire dataset period?

7.What is the average volume traded on each recorded date?

8.How many trading days are included in the dataset?

9.What is the percentage change in the NIFTY index from the beginning to the end of the dataset period?

10.What is the average daily price range (High - Low)?

11.How many times did the NIFTY index close higher than the previous day's close?

12.How many times did the NIFTY index close lower than the previous day's close?

13.How many trading days experienced a positive percentage change?

14.How many trading days experienced a negative percentage change?

15.What is the highest volume of trades recorded on a single day?

16.What is the average closing price for each month?

17.What is the average daily trading volume for each month?

18.What is the average daily price range for each month?

19.How many trading days experienced a price increase of more than 1%?

20.How many days had no trading activity (zero volume)?

21.How many times did the NIFTY index close exactly at its opening price?

22.How many times did the NIFTY index cross a certain threshold (e.g., 10,000 points)?

23.How many days had the highest opening price?

24.How many days had the highest closing price?

25.How many days had the opening price higher than the closing price?

26.What is the average opening price?

27.What is the average high price?

28.What is the average low price?

29.What is the average volume traded?

30.What the average closing price?

Getting Started:
To replicate this analysis or build on it, follow these steps:

1.Clone the repository:

git clone htt

2.Import the Dataset into MySQL:

Import the nifty_data.csv file into your MySQL database.

Use the provided nifty_data.

sql script to create the necessary table and load the data.

3.Run SQL Queries:

You can run the SQL queries provided in the queries/ directory or modify them to explore other aspects of the data.

4.Perform Analysis:

Use the queries and results to perform your analysis, explore trends, and test trading strategies.

Conclusion:

This project demonstrates the power of SQL for conducting stock market analysis and gaining valuable insights into the behavior of the Nifty index. By utilizing MySQL and the given dataset, users can explore the Indian stock market, test trading strategies, and conduct data-driven research.

Feedback and Suggestions:
Thank you for visiting my repository! If you have any questions or feedback, feel free to reach out.

I’d love to hear your thoughts, feedback, and suggestions! Feel free to connect with me:

LinkedIn: Annapoorna N

Email: annapoornan532@gmail.com

Looking forward to connecting and exchanging ideas!

✨ Support this project!
If you found this project helpful or interesting, please consider giving it a ⭐ on GitHub! Your support helps keep the project active and encourages further development.

Thank you for your support! 💖
