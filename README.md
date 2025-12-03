# Azure-DE-Project
This project demonstrates an end-to-end cloud data engineering pipeline built using Azure Data Factory, Azure Databricks, Azure SQL Database, ADLS Gen 2 and Amazon S3.

🔧 Project Overview

Designed and deployed a scalable data pipeline that ingests data from Amazon S3, processes it using Databricks, and loads it into Azure SQL DB for reporting and analytics.

📌 Key Components

🚀 Azure Data Factory (ADF)

Pipeline creation, parameterization, and orchestration

Storage event-based triggers for automated ingestion

Integration with Databricks notebook execution

🚀 Azure Databricks

Data transformation logic using notebooks

Generic mount setup with secure storage keys

Interactive cluster-based development

🚀 Azure SQL Database

Lookup table creation

Loading curated data into final tables

Performing table joins for reporting

🚀 Amazon S3 to Azure Integration

Ingesting raw data from S3

Multi-stage ingestion (raw → staging → curated)