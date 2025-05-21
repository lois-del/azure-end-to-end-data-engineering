# Azure Data Engineering Pipeline: SQL Server → Data Lake → Databricks

This project showcases a real-world Azure data pipeline using:

- **Azure Data Factory** for orchestrating ingestion from a SQL Server source
- **Azure Data Lake Storage Gen2** as the central data repository
- **Azure Databricks** to implement the **medallion architecture** (bronze → silver → gold)
- Optional: **Power BI** for reporting and dashboarding

## Key Features
- 📥 Ingests raw data from SQL Server using ADF
- 🔁 Bronze-to-Silver transformations in Databricks using PySpark
- 🔍 Monitoring pipeline runs and logging events
- 📊 (Optional) Visualize insights using Power BI

## Architecture
A high-level overview of the components used:
