# Atlikan-Data-Engineering-Project
# End-to-End FMCG Data Engineering Project

## Project Overview
This project implements an end-to-end data engineering pipeline using **Databricks** to consolidate sales data from two companies, Atlon and Sports Bar.

The goal is to integrate data from different sources, clean inconsistent records, transform datasets, and create a unified data platform for business intelligence and analytics.

## Technologies Used
- Python
- SQL
- PySpark
- Databricks
- AWS S3
- Delta Lake
- Medallion Architecture (Bronze, Silver, Gold)
- Databricks Genie
- Databricks Dashboards

## Architecture

The project follows the Medallion Architecture:

1. **Bronze Layer:** Ingests and stores raw data from AWS S3.
2. **Silver Layer:** Cleans and transforms data by handling duplicates, null values, inconsistent formats, and data quality issues.
3. **Gold Layer:** Stores processed, business-ready datasets and consolidates data from both companies.

## Key Features
- Data ingestion from AWS S3.
- Batch and incremental data processing.
- Data cleaning and transformation using PySpark.
- Data integration between two companies.
- Delta Lake MERGE/UPSERT operations.
- Automated data pipeline orchestration.
- Business intelligence dashboards.
- AI-powered data exploration using Databricks Genie.

## Business Outcome
The solution provides a unified data foundation that enables management to analyze sales performance, revenue, product trends, customer activity, and other business metrics across both companies.

## Learning Objectives
This project demonstrates practical data engineering skills, including ETL pipeline development, cloud data storage, data quality management, data integration, and business intelligence.

