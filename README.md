# SQL Data Warehouse
## Building the Data Warehouse (Data Engineering)

### Objective
Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical rpeorting and informed decision-making

### Specification
- **Data Sources:** Import data from two source systems (ERP & CRM) provided as CSV files.
- **Data Quality:** Cleanse & resolve data quality issues prior to analysis.
- **Integration:** Combine both sources into a single, user firendly model designed for analytical queries.
- **Scope:** Focus on the latest dataset only; historization of data is not required.
- **Documentation:** Provide clear documentation of the data model to support both business stakeholders and analytics.

## Design Data Architecture (Medallion Architecture)
**Bronze Layer** : 
Raw, unprocessed data as-is from sources

**Silver Layer** :
Clean & Standardized data 
  - Data Cleaning
  - Data Standardization
  - Data Normalization
  - Derived Columns
  - Data Enrichment

**Gold Layer** :
Business-Ready data
  - Data Integration
  - Data Aggregation
  - Business Logic & Rules
Data Modelling:
  - Star Schema
  - Aggregated Objects
  - Flat Tables

![Alt text](path/to/Medallion%20Architecture.png4)

