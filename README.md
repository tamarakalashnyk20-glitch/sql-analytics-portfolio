# sql-analytics-portfolio
## SQL Query Description
## E-commerce Account & Email Activity Analysis

This SQL query analyzes e-commerce account creation and email engagement activity across different countries and customer segments.  

The query combines account and email metrics using `UNION ALL`, aggregates engagement statistics, calculates country-level totals, and ranks countries based on subscriber growth and email activity using window functions.

Key metrics included:
- account creation count,
- sent emails,
- opened emails,
- email visits,
- country-level totals,
- country rankings.

The query was built in BigQuery using:
- CTEs,
- window functions,
- aggregations,
- joins,
- DENSE_RANK(),
- UNION ALL.
