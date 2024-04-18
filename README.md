## Sales Insights using-SQL & Power-BI

Project description,functions,queries written,environment used are mentioned in readme.

### Sales Data - Cleaning & Exploration
Removing and adding columns as necessary in the tables and preparing the database tables for Analysis.
Data subset collected in [SQL dump file](https://github.com/vishnu55510/Sales_Insights-SQL-Power-BI/blob/main/Database%20dump.sql) and loaded to SQL server for exploring the data tables.
Tables:
1. Customers
2. Date
3. Markets
4. Products
5. Transactions

### SQL queries for data cleaning and exploration
Data acquired is cleansed using SQL queries here.
[click here to view code](https://github.com/vishnu55510/Sales_Insights-SQL-Power-BI/blob/main/Data%20Cleaning%20%26%20Exploration%20using%20SQL.sql)

### Analysis using SQL
[Click here to view code](https://github.com/vishnu55510/Sales_Insights-SQL-Power-BI/blob/main/Data%20Analysis%20using%20SQL.sql)
Queries:
1. All tables and their rows in sales schema
2. Date range in date table
3. Revenue generated in 2020 and 2019.
4. Currency and their count
5. Total sales amount collected by each market
6. Sales quantity ordered from each market on each day
7. Sales across all markets in each year
8. Categorizing Product sales based on sales quantity in each order
9. Calculating revenue Contribution percentage for each market across all years
10. Finding market name that made maximum sales

### Data Visualization using [Power BI dashboard](https://github.com/vishnu55510/Sales_Insights-SQL-Power-BI/blob/main/Sales%20Insights%20-%20Visualization.pbix)
Getting data into BI through SQL dump and performing Data Visualization and analysing of hardware store products across different regions, observing profit analysis and revenue trend of the company.

### Insights:
1. In this dashboard, we can see company has generated total revenue in 4 years ₹ 985M, total profit margin ₹24.7M, Profit margin% 2.5%, Sales Qty ₹2M. in 2020 company has generated 2. total revenue of ₹ 142M by selling a total of 350K and earned a profit of ₹ 2.1M.
3. In 4 years Delhi NCR is our largest market in terms of revenue with ₹ 520M and total contribution of 52.8% with total revenue but if you look at the profit margin Delhi NCR is generating only 2.3% profit margin.
4. If we check the profit margin then here In 2020 Bhubaneshwar comes into the picture which is generating the highest profit margin of 10.48%. Similarly, if we can check the Profit Contribution % by Market then here Mumbai is the largest player with 23.89% of total contribution in total profit.
5. In 4 years Bengaluru generating the lowest profit margin of -20.8%.if we can check the Profit Contribution % by Market then here also Bengaluru is the Lower with -0.3% of total contribution in total profit.
6. In our top 5 customers, the Electricalsara Stores is our biggest customer who has generated total ₹ 413 M revenue generated in 4 years.
7. In our top 5 products,the Prod318 is our highest product has generated total ₹ 69M revenue generated in 4 years.
8. In product type Distribution has generated the revenue of ₹494M and ownbrand revenue is ₹494M generated in entire 4 years.
Revenue Trend is showing that in June 2020 revenue has been decreased drastically compared to the revenue last year and the profit margin was the least in April 2020.
9. Sales were rapidly decreasing in 2020 compared to 2019 by around 57.7%.
10. Highest revenue generated from Markets such as Delhi NCR, Mumbai, Ahmedabad, Bhopal, Nagpur, and so on.
11. Highest quantities sold in the Market such as Delhi NCR, Mumbai, Nagpur, Kochi, Ahmedabad, and so on.
12. Majority of the sales were takes place in the month of January followed by November and March.

Dashboard of Performance Tracking of sales for quick view:
![image](https://user-images.githubusercontent.com/106775145/209099717-295fd41e-fffc-4bdb-83ab-a50bbef24b86.png)




