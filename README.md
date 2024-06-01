# Big_Data_engineering
## StackOverflow Data Engineering Project
### Project Objectives
Build data pipelines to ingest data from various sources.
Clean and prepare the data for analysis.
Train machine learning models for tag prediction and question quality prediction.
Automate data pipelines for efficiency.
Visualize insights and results.
### Tools and Technologies
Azure Data Factory: For building data pipelines.
AWS RDS: For hosting the Postgres database.
Azure Blob Storage and AWS S3: For data storage.
Azure Data Lake: For data storage and management.
Spark: For data cleaning and preparation.
Apache Airflow: For pipeline automation.
Azure Synapse: For data warehousing and visualization.
Databricks: For collaborative data analysis and dashboards.
### Project Workflow
Data Ingestion: Data was ingested from AWS RDS (Postgres DB), Azure Blob Storage, and AWS S3 into Azure Data Lake using Azure Data Factory.
Data Transformation:
Data cleaning and preparation were performed using Spark.
Machine learning models were trained using Spark MLlib for tag prediction and question quality prediction.
Pipeline Automation: Apache Airflow was integrated with Azure Data Factory to automate and manage data pipelines.
Data Visualization:
Azure Synapse was used to visualize the top 5 topics in StackOverflow posts and the distribution of question quality.
Databricks was utilized to create a dashboard for exploring and gaining insights into the characteristics of StackOverflow developers.
