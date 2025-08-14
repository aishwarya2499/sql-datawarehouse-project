# sql-datawarehouse-project 🏬
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights

🏗️ Data Architecture

The data architecture for this project follows Medallion Architecture Bronze, Silver and Gold layers.
1. Bronze Layer: Stores raw data as-is from the source systems. Data is ingested from CSV Files into SQL Server Database.
2. Silver Layer: This layer includes data cleansing, standardization, and normalization processes to prepare data for analysis.
3. Gold Layer: Houses business-ready data modeled into a star schema required for reporting and analytics.

🚀 Objective

Developed a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

Specifications

🧱 Data Sources: 
1. Importing data from two source systems (ERP and CRM) provided as CSV files.
2. Data Quality: Cleansing and resolving data quality issues prior to analysis.
3. Integration: Combining both sources into a single, user-friendly data model is designed for analytical queries.
4. Scope: Focus on the latest dataset only, historization of data is not required.
5.Documentation: Provide clear documentation of the data model to support both business stakeholders and analytics teams.
