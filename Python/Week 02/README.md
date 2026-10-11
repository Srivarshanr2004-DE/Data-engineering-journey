# Retail POS & Inventory ETL Pipeline
A Data Engineering mini-project built with Pandas to extract, clean, transform, and load retail sales and inventory data.

## Business Scenario
You receive daily messy sales transactions (CSV) and a master product inventory sheet (JSON). Your job is to clean the data, join them, calculate key business metrics, and load the final reports into clean CSV files for a BI dashboard.

## Tasks
1. Extract data from `data/raw/`.
2. Clean sales data (remove duplicates, handle missing values, fix negative quantities).
3. Clean inventory data (standardize categories).
4. Merge sales and inventory data.
5. Aggregate data (calculate daily revenue, find low stock items).
6. Load processed data to `data/processed/`.
