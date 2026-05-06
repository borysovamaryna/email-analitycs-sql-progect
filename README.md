#  Email Analytics SQL Project

##  Description

This project contains a SQL query for analyzing:

- user accounts  
- email campaigns  
- email interactions (opens and clicks)  

The goal is to understand user engagement and email performance across countries and time periods.


##  What was implemented

The query includes:

- use of CTEs (`WITH` statements)  
- joining data from multiple tables  
- calculation of key metrics:
  - number of user accounts  
  - number of sent emails  
  - email opens  
  - email clicks  
- aggregation of results by country  
- ranking countries using `DENSE_RANK`  


##  Query structure

### `account_info`
User account-level information.

### `messages_info`
Email activity data (sent emails, opens, clicks).

### `final_info`
Combined dataset with account and email activity data.

### `country_totals`
Aggregated metrics grouped by country.

### `country_ranks`
Ranking of countries based on key performance metrics.

### `Final SELECT`
Final analytical output used for reporting and insights.


##  Technologies

- SQL (BigQuery / standard SQL)


##  Results

The analysis provides:

- Top 10 countries by number of user accounts  
- Top 10 countries by number of sent emails  
- Detailed breakdown of user engagement by date and key metrics  


##  How to use

1. Connect to the database  
2. Run `queries.sql`  
3. Use the output for email performance and user engagement analysis  

## Results in Looker Studio
![Looker](looker-studio-visual)


