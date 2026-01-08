# FlexiMart Data Architecture Project
**Student Name:** Ayush  
**Student ID:** [Your ID]  
**Email:** [Your Email]  
**Date:** [Date]

## Project overview
End-to-end data architecture: ETL from raw CSVs into MySQL (OLTP), schema documentation, business SQL queries, NoSQL analysis with MongoDB, and a dimensional data warehouse with OLAP analytics.

## Repository structure
- part1-database-etl/
  - etl_pipeline.py
  - schema_documentation.md
  - business_queries.sql
  - data_quality_report.txt
  - requirements.txt
- part2-nosql/
  - nosql_analysis.md
  - mongodb_operations.js
  - products_catalog.json
- part3-datawarehouse/
  - star_schema_design.md
  - warehouse_schema.sql
  - warehouse_data.sql
  - analytics_queries.sql
- data/
  - customers_raw.csv
  - products_raw.csv
  - sales_raw.csv

## Technologies used
- Python 3.x, pandas, mysql-connector-python
- MySQL 8.0
- MongoDB 6.0

## Setup instructions

### Databases
```bash
mysql -u root -p -e "CREATE DATABASE fleximart;"
mysql -u root -p -e "CREATE DATABASE fleximart_dw;"
