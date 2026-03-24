# Customer Shopping Behavior Analysis

This repository contains an end-to-end retail analytics workflow using Python, SQL, and Power BI.

## Project Goals

- Prepare and clean transactional customer shopping data
- Engineer analysis-ready features for segmentation and behavior tracking
- Export curated data to SQL databases for querying
- Build dashboard-ready outputs for reporting and presentations
- Generate business insights from customer behavior patterns

## Project Structure

```text
Sales Data Analysis/
|-- data/
|   `-- raw/
|       `-- customer_shopping_behavior.csv
|-- notebooks/
|   `-- customer_shopping_behavior_analysis.ipynb
|-- sql/
|   `-- customer_behavior_queries.sql
|-- dashboards/
|   `-- customer_behavior_dashboard.pbix
|-- reports/
|   |-- business_problem_document.pdf
|   `-- customer_shopping_behavior_analysis.pdf
|-- presentations/
|   `-- customer_shopping_behavior_analysis.pptx
|-- LICENSE
`-- README.md
```

## Notebook Highlights

The notebook `notebooks/customer_shopping_behavior_analysis.ipynb` includes:

- Modular helper functions (imputation, renaming, feature creation, and column handling)
- Cleaner naming conventions for variables and transformations
- Better inline comments for clarity without changing core logic
- SQL export helper functions for:
  - PostgreSQL
  - MySQL
  - SQL Server
- Additional insights:
  - Revenue by category
  - Average review rating by season
  - Spend patterns by age group and subscription status

## How to Run

1. Open the notebook: `notebooks/customer_shopping_behavior_analysis.ipynb`
2. Run cells in order
3. Optional: configure database credentials and run export function cells
4. Use SQL scripts from `sql/customer_behavior_queries.sql`
5. Open `dashboards/customer_behavior_dashboard.pbix` for visualization

## Suggested Python Dependencies

Install as needed in your environment:

- `pandas`
- `sqlalchemy`
- `psycopg2-binary` (PostgreSQL)
- `pymysql` (MySQL)
- `pyodbc` (SQL Server)

