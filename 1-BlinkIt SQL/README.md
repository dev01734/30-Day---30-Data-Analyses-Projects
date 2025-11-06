
# BlinkIt SQL — Data Exploration Project

This small project contains CSV data exports and a Jupyter notebook used to explore BlinkIt order data with SQL-style analysis. It is intended for data analysis practice, quick exploratory queries, and answering the questions listed in `Questions.txt`.

## Contents

- `blinkit SQl.ipynb` — Jupyter notebook with exploratory analysis (SQL/pandas queries and visualizations).
- `Customers.csv` — customer-level information.
- `Orders.csv` — order-level metadata (order id, customer id, order date, etc.).
- `OrderDetails.csv` — line-level order items, quantities, and prices.
- `Questions.txt` — a short list of analysis questions to answer using the data.

## Goal

Use the notebook and CSV files to practice SQL-style analytics: joins, aggregates, time-series analysis, segmentation, and common retail KPIs (orders, revenue, AOV, repeat customers, top products).

## How the notebook is organized

- A first section loads the three CSVs into dataframes.
- Next sections perform cleaning and type conversions (dates, numeric fields).
- The analysis sections demonstrate joins between `Orders` and `OrderDetails`, group-bys for revenue and order counts, time-based aggregations, and customer-level metrics.
- Visualizations show trends and top-N breakdowns.

