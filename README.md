# sql-data-warehouse-project

## Overview
I built an ETL process in SQL to gather data from different sources, clean and transform it, and load it into a data warehouse for easier analysis and reporting.
<img width="931" height="483" alt="image" src="https://github.com/user-attachments/assets/ce90e170-3085-4e3c-b369-091fb8b56923" />
## Technologies Used
- **SQL Server** — main database and data warehouse
- **T-SQL** — data cleaning, transformation, and modeling
- **SSIS** — ETL orchestration and data pipeline automation
- **Bronze / Silver / Gold** architecture — layered data modeling for ingestion, refinement, and analytics

## Data Sources
- **CRM:** Salesforce, HubSpot  
- **ERP:** SAP, Oracle NetSuite, Odoo  
- **Other Sources:** Excel files, CSV imports, Web APIs, Third-party integrations

  
## ETL Process
1. **Extract:** Pull data from multiple sources.
2. **Transform:** Clean, standardize, and apply business rules.
3. **Load:** Insert processed data into the data warehouse.

## Data Warehouse Design
- **Fact Tables:sales
- **Dimension Tables:products,customers
- **Schema Type:** Star Schema
<img width="621" height="345" alt="image" src="https://github.com/user-attachments/assets/ccb9bbf3-f58f-4d20-871d-46ae76d0e962" />

## Key Features
- Data validation and quality checks
- Incremental loading
- Optimized SQL queries for reporting

## Outcome
- Centralized data for analytics
- Simplified reporting and insights generation
- Foundation for business intelligence dashboards

