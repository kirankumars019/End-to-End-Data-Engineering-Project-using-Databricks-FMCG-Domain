# End-to-End-Data-Engineering-Project-using-Databricks-FMCG-Domain
This project demonstrates an end-to-end data engineering pipeline using Databricks Free Edition. It covers data ingestion, cleaning, transformation with Apache Spark, and storage using Delta Lake. The medallion architecture (Bronze, Silver, Gold) is used, with transformations implemented in PySpark and SQL for scalability and reliability.

# Project Overview

This repository contains a complete data engineering pipeline that demonstrates how to:

1) Ingest raw data from sources - S3
2) Perform scalable transformations using Apache Spark on Databricks
3) Store transformed data in optimized formats
4) Build a reliable analytical dataset ready for visualization or ML

# Key Features

1) Data Ingestion -

  Ingest raw datasets from different sources (e.g., CSV, JSON).

2) Spark-based Transformations -

  Use Apache Spark on Databricks to clean, enrich, and structure data.

3) Delta Lake Storage-
 
  Store intermediate and curated data in Delta Lake tables for reliability and performance.

4) Modular Notebooks -

  Step-by-step Databricks notebooks for each stage of the pipeline.

5) Beginner-Friendly-

  Designed to help you learn real-world data engineering workflows without paid tools

# Workflow

1) Load raw data from local or cloud sources -S3

2) Dimension Data Processing - Clean and validate data using Spark - Bronze Layer, Silver Layer

3) Dimension Data Processing - Transform and enrich datasets - Gold Layer

4) Fact Historical Data Processing  - Persist structured data using Delta Lake - Merging Transformed Child Gold data to Parent Gold Data
   
5) Fact Incremental Data Processing  - Merging Transformed Incremental(Current data) Child data to Parent Gold Data

6) Query optimized data for analytics / reporting 
