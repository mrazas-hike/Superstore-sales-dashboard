# Superstore Sales Analysis Dashboard: Regional, Category and Monthly Trends in Excel

**Team members:**

| Name | Enrollment No. |
|---|---|
| Mohd Talha | 2600101015 |
| Mohammad Raza Siddiqui | 2600105456 |
| Mohd Fuzail | 2600101783 |
| Ismaeel | 2600101660 |

**Course / Assignment:** Semester Project (Assignment 2), First Year, Excel

## Overview
An Excel dashboard that analyses four years of retail sales (Jan 2015 to Dec 2018) to find top-performing regions, categories, products and seasonal trends. Three dropdown filters (Year, Region, Category) update every KPI card and chart.

## Dataset
- **Source:** Superstore Sales dataset from Kaggle (`superstore_final_dataset.csv`)
- **Size:** 9,800 rows and 18 columns (orders, dates, customers, location, product, sales)
- **Limitation:** the dataset has no Profit column, so the analysis is sales-based.

## Files in this repository
| File | Description |
|---|---|
| `Superstore_Sales_Dashboard.xlsx` | Final workbook (Dashboard, Summary, Data sheets) |
| `superstore_final_dataset.csv` | Original dataset |
| `dashboard_1.png`, `dashboard_2.png` | Dashboard screenshots |
| `dashboard_filtered.png` | Dashboard with the Year filter applied |

## Workbook structure
- **Dashboard:** KPI cards (Total Sales, Total Orders, Average Order Value, Top Region, Top Category), 8 charts, filters and written insights.
- **Summary:** formula-based tables (SUMIFS) behind every chart.
- **Data:** cleaned data as an Excel Table named `SalesData`, with helper columns Order_Year, Order_Month, Month_Num and order-count flags.

## Steps followed
1. Imported the CSV into Excel and fixed the date columns (DD/MM/YYYY).
2. Cleaned the data: removed 1 exact duplicate row, filled 11 blank postal codes (Burlington, Vermont, 05408).
3. Converted the data to a Table and added Year, Month and order-flag columns.
4. Built summary tables with SUMIFS and COUNT-style flags.
5. Created charts and KPI cards, and added dropdown filters using data validation.
6. Wrote the insights from the results.

## Key insights
1. **West** is the top region at about $710K (31.4% of sales); South is the weakest at $389K.
2. **Technology** is the top category at $827K (36.6%).
3. **Phones** ($328K) and **Chairs** ($323K) are the best sub-categories.
4. Sales peak in **November, December and September**; February is the lowest month.
5. Yearly sales fell 4.2% in 2016, then grew 30.6% in 2017 and 20.3% in 2018 (to $722K).
6. **Consumers** make up 50.8% of sales; **Standard Class** is used for about 60% of orders.

## Tools used
Microsoft Excel (Tables, SUMIFS, data validation, charts).

## How to use
Open the workbook, click **Enable Editing**, go to the **Dashboard** sheet and use the yellow cells (Year, Region, Category) to filter.
