# -Azure-Healthcare-data-enginnering
An end-to-end healthcare data engineering project built on Microsoft Azure using modern data engineering practices.

This project demonstrates how healthcare data is ingested, transformed, secured, and analyzed using a production-grade cloud architecture.

Domain: Healthcare Revenue Cycle Management (RCM)

The pipeline processes healthcare datasets through multiple layers:

🟫 Bronze Layer → Raw Data Ingestion
⬜ Silver Layer → Data Cleaning & Transformation
🟨 Gold Layer → Business Analytics & Reporting

🏗 Architecture

Azure SQL Database
        ↓
Azure Data Factory
        ↓
Azure Data Lake Storage Gen2
        ↓
Bronze Layer
        ↓
Silver Layer
        ↓
Gold Layer
        ↓
Power BI / Analytics

⚡ Features

✅ Azure SQL → ADLS Gen2 ingestion
✅ Bronze / Silver / Gold architecture
✅ Full load & Incremental load processing
✅ Audit logging implementation
✅ SCD Type 2 implementation
✅ Delta Lake processing
✅ Secret management using Azure Key Vault
✅ Managed Identity for secure access
✅ Production-grade ETL pipeline

🛠 Tech Stack
Azure Data Factory
Azure Databricks
Azure Data Lake Storage
Azure SQL Database
Azure Key Vault
Delta Lake
Python
PySpark
SQL

📂 Project Structure
azure-healthcare-data-engineering/
│
├── datasets/
├── sql_scripts/
├── adf_pipeline/
├── databricks_notebooks/
├── bronze_layer/
├── silver_layer/
├── gold_layer/
└── README.md

🔄 Data Pipeline Flow
Extract data from Azure SQL Database
Load raw data into ADLS Gen2
Process raw data in Bronze Layer
Clean and transform in Silver Layer
Apply SCD Type 2 and incremental logic
Generate business KPIs in Gold Layer
Visualize insights using dashboards

📊 Key Learnings
Building real-world ETL pipelines
Implementing Medallion Architecture
Data governance and security
Incremental processing techniques
Healthcare analytics use cases
👩‍💻 Author

Shravya N S
Aspiring Azure Data Engineer 🚀
