# EV Market Analysis - SQL Queries and Results

This repository contains SQL queries and their result data related to electric vehicle (EV) market analysis. The goal is to provide examples for analyzing EV sales, market share, and related metrics across countries and years.

---

1. Total EV Sales per Country
   
| Country | total\_sales |
| ------- | ------------ |
| USA     | 5,200,000    |
| China   | 4,900,000    |
| Germany | 3,500,000    |
| Norway  | 2,800,000    |
| France  | 2,200,000    |

2. Average EV Market Share per Year

| Year | avg\_market\_share (%) |
| ---- | ---------------------- |
| 2015 | 5.25                   |
| 2016 | 6.80                   |
| 2017 | 9.35                   |
| 2018 | 11.70                  |
| 2019 | 15.22                  |
| 2020 | 19.84                  |
| 2021 | 22.36                  |
| 2022 | 24.90                  |
| 2023 | 27.51                  |
| 2024 | 28.73                  |

3. Average GDP per Capita vs Average EV Sales per Country

| Country | avg\_gdp\_per\_capita | avg\_sales |
| ------- | --------------------- | ---------- |
| USA     | 68,500                | 28,500     |
| Norway  | 74,200                | 26,300     |
| Germany | 58,100                | 25,900     |
| France  | 52,400                | 24,500     |
| China   | 15,200                | 21,100     |

4. Total EV Sales by EV Type

| EV\_Type | total\_sales |
| -------- | ------------ |
| BEV      | 8,400,000    |
| PHEV     | 5,900,000    |
| HEV      | 4,800,000    |

5. Average EV Sales by Government Incentives (YES/NO)

| Govt\_Incentives | avg\_sales |
| ---------------- | ---------- |
| YES              | 26,400     |
| NO               | 18,900     |



## Files Included

- `queries.sql`  
  Contains sample SQL queries used for extracting key EV market insights such as total sales by country, market share trends, and government incentives impact.

- `ev_queries_combined_results.csv`  
  A combined CSV file with dummy results for all the SQL queries. Each row indicates which query the data belongs to, with appropriate columns.

---

## Summary of Queries

1. **Total EV Sales per Country**  
   Sum of EV sales in USD grouped by country.

2. **Average EV Market Share per Year**  
   Yearly average EV market share percentage.

3. **Average GDP per Capita vs Average EV Sales per Country**  
   Average GDP per capita and average EV sales grouped by country.

4. **Total EV Sales by EV Type**  
   Sales totals grouped by EV type (BEV, PHEV, HEV).

5. **Average EV Sales by Government Incentives**  
   Comparison of average sales with and without government incentives.

---
# EV Market Analysis - SQL Query Results

This file contains result data generated from the SQL queries analyzing the electric vehicle (EV) market.

total_ev_sales_per_country.csv

average_ev_market_share_per_year.csv

avg_gdp_vs_avg_ev_sales.csv

total_ev_sales_by_ev_type.csv

avg_ev_sales_by_govt_incentives.csv

---

## About the CSV: `ev_queries_combined_results.csv`

The CSV consolidates the results of five key SQL queries, each tagged by query number and description for easy identification:

| Query Number | Description                                   |
| ------------ | --------------------------------------------- |
| 1            | Total EV Sales per Country                    |
| 2            | Average EV Market Share per Year              |
| 3            | Average GDP per Capita vs Average EV Sales   |
| 4            | Total EV Sales by EV Type                      |
| 5            | Average EV Sales by Government Incentives     |

---

---

## How to Use

- You can run the SQL queries on your EV market database after adjusting table/column names as needed.
- Use the CSV dummy data to practice data visualization or analytics.
- Extend queries for deeper analysis or reporting.

---

Feel free to open issues or contribute improvements!

---

*Created by Sravan*

