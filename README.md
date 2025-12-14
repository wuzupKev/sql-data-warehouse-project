# sql-data-warehouse-project

## Overview
I built an ETL process in SQL using the **Medallion Architecture (Bronze–Silver–Gold)** to gather data from different sources, progressively clean and transform it, and load it into a data warehouse optimized for analysis and reporting.

<img width="931" height="483" alt="image" src="https://github.com/user-attachments/assets/ce90e170-3085-4e3c-b369-091fb8b56923" />
## Technologies Used
- **SQL Server** — main database and data warehouse
- **T-SQL** — data cleaning, transformation, and modeling
- **SSIS** — ETL orchestration and data pipeline automation
- **Medallion Architecture (Bronze / Silver / Gold)** — layered data modeling for ingestion, refinement, and analytics

## Data Sources
- **CRM:** Salesforce, HubSpot  
- **ERP:** SAP, Oracle NetSuite, Odoo  
- **Other Sources:** Excel files, CSV imports, Web APIs, Third-party integrations

## ETL Process (Medallion Architecture)
1. **Bronze Layer (Raw):**
   - Extract data from multiple sources.
   - Store raw, unprocessed data as-is.
   - Preserve source structure for traceability and auditing.

2. **Silver Layer (Cleaned & Conformed):**
   - Clean and standardize data.
   - Handle nulls, duplicates, and invalid records.
   - Apply business rules and data transformations.

3. **Gold Layer (Analytics Ready):**
   - Build fact and dimension tables.
   - Optimize data for reporting and analytics.
   - Serve as the source for BI tools and dashboards.

## Data Warehouse Design
- **Fact Tables:** sales  
- **Dimension Tables:** products, customers  
- **Schema Type:** Star Schema

<img width="621" height="345" alt="image" src="https://github.com/user-attachments/assets/ccb9bbf3-f58f-4d20-871d-46ae76d0e962" />

## Key Features
- Data validation and quality checks
- Incremental loading
- Optimized SQL queries for reporting

## Outcome
- Centralized and reliable data for analytics
- Simplified reporting and insight generation
- Solid foundation for business intelligence dashboards

