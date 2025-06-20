-- 1. Total EV Sales per Country
SELECT Country, SUM(EV_Sales_USD) AS total_sales
FROM ev_sales_data
GROUP BY Country
ORDER BY total_sales DESC;

-- 2. Average EV Market Share per Year
SELECT Year, AVG(EV_Market_Share) AS avg_market_share
FROM ev_sales_data
GROUP BY Year
ORDER BY Year;

-- 3. Average GDP per Capita vs Average EV Sales per Country
SELECT Country,
       AVG(GDP_per_Capita) AS avg_gdp_per_capita,
       AVG(EV_Sales_USD) AS avg_sales
FROM ev_sales_data
GROUP BY Country
ORDER BY avg_sales DESC;

-- 4. Total EV Sales by EV Type
SELECT EV_Type, SUM(EV_Sales_USD) AS total_sales
FROM ev_sales_data
GROUP BY EV_Type
ORDER BY total_sales DESC;

-- 5. Average EV Sales by Government Incentives (YES/NO)
SELECT Govt_Incentives, AVG(EV_Sales_USD) AS avg_sales
FROM ev_sales_data
GROUP BY Govt_Incentives;
