# YouTube-Data-Engineering-Project---AWS

An end-to-end AWS data engineering project implementing a production-style data lake architecture.
The pipeline ingests YouTube trending data, processes it using AWS services, and delivers insights through an interactive Power BI dashboard.

 Data Source

YouTube Trending Videos Dataset (Kaggle)

Batch data used to simulate real-world analytics workloads

 Architecture
Kaggle Data
   ↓
Amazon S3 (Raw / Landing)
   ↓
AWS Glue ETL
   ↓
Amazon S3 (Cleansed)
   ↓
Amazon S3 (Analytics)
   ↓
Amazon Athena
   ↓
Power BI Dashboard

 Pipeline Highlights

Built a layered AWS data lake using Amazon S3

Implemented ETL pipelines with AWS Glue

Managed metadata using Glue Data Catalog

Orchestrated workflows with AWS Step Functions & Lambda

Enabled serverless querying using Amazon Athena

Created an interactive Power BI dashboard for insights

 Dashboard Insights

Trending category performance

Engagement metrics (views, likes, comments)

Regional and time-based trends

 Tech Stack

AWS S3, Glue, Glue Data Catalog, Lambda, Step Functions, Athena, Power BI, Python, SQL


