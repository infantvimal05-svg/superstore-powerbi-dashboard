# Superstore Sales Dashboard (Power BI)

Interactive Power BI dashboard built on 9,994 orders across 4 regions and 17 sub-categories (2014-2017).

## Dashboard Preview

### Page 1: Sales Performance Overview
![Page 1](screenshots/dashboard_page1_overview.png)

### Page 2: Product and Profitability Analysis
![Page 2](screenshots/dashboard_page2_profitability.png)

## Features
- KPI cards: Total Sales, Total Profit, Total Orders
- Monthly sales trend
- Sales by category, region, segment and ship mode
- Profit by category, sub-category and region
- Sales and profit by year
- Slicers for year, category, region and segment
- Two report pages with page navigation

## Dataset
- Superstore-format sales data: 9,994 rows, 21 columns
- 4 regions, 17 sub-categories, orders from 2014 to 2017
- Note: the data is sample data generated in the Superstore format for practice.

## Key Business Insights
1. **Technology** is the top category by sales (2.25M), ahead of Furniture (1.80M) and Office Supplies (1.21M).
2. **Furniture loses money** (about -171K profit) despite high sales. Tables, Bookcases and Chairs drive this.
3. **East** is the most profitable region (36K). West has the highest sales (1.70M), and Central has the lowest profit (10K).
4. **Copiers** are the most profitable sub-category (about 114K). Tables are the biggest loss (about -132K).
5. Sales **grew every year**, from 0.97M in 2014 to 1.69M in 2017, and peak in November and December.
6. The **Consumer** segment brings 56% of sales (2.94M).
7. **Standard Class** is the most used ship mode (3.15M, about 60% of sales). The overall profit margin is only 1.7%.

## KPIs
| Metric | Value |
|---|---|
| Total Sales | 5,265,797 |
| Total Profit | 91,917 |
| Total Orders | 5,009 |

## How to Use
1. Download the `.pbix` file.
2. Open it in Power BI Desktop.
3. Use the slicers and click charts to filter the data.

## Tools and Skills
Power BI Desktop, Power Query, DAX measures, data modelling, data visualization, dashboard design

## Related Project
[Superstore Sales Analysis (SQL, PostgreSQL)](https://github.com/infantvimal05-svg/superstore-sql-analysis)
