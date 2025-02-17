## Introduction
Walmart, the largest retail store in the U.S., has expanded its e-commerce operations, generating $80 billion in sales by the end of 2022, which is 13% of its total revenue. Public holidays, such as the Super Bowl, Labor Day, Thanksgiving, and Christmas, significantly influence Walmart's sales patterns.

This project focuses on developing a data pipeline to analyze supply and demand trends around holidays using two data sources: grocery sales data stored in a PostgreSQL database and complementary data in a Parquet file.


## Key Tasks:
## Data Integration & Cleaning
 - Merge grocery_sales and extra_data based on store and date information.
- Extract relevant features: Store_ID, Month, Dept, IsHoliday, Weekly_Sales, CPI, Unemployment.
## Data Aggregation & Analysis
- Conduct a preliminary analysis of monthly sales trends across Walmart stores.
- Store aggregated results in agg_data, summarizing total Weekly_Sales per month.
## Output & Storage
