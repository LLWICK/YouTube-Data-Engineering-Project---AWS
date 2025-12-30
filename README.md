# YouTube-Data-Engineering-Project---AWS

An end-to-end AWS data engineering project implementing a production-style data lake architecture.
The pipeline ingests YouTube trending data, processes it using AWS services, and delivers insights through an interactive Power BI dashboard.

 Data Source

YouTube Trending Videos Dataset (Kaggle) - https://www.kaggle.com/datasets/datasnaek/youtube-new

Batch data used to simulate real-world analytics workloads

 Architecture
Kaggle Data
   ->
Amazon S3 (Raw / Landing)
   ->
AWS Glue ETL
   ->
Amazon S3 (Cleansed)
   ->
Amazon S3 (Analytics)
   ->
Amazon Athena
   ->
Power BI Dashboard

 Pipeline Highlights

1. Built a layered AWS data lake using Amazon S3

2. Implemented ETL pipelines with AWS Glue

3. Managed metadata using Glue Data Catalog

4. Orchestrated workflows with AWS Step Functions & Lambda

5. Enabled serverless querying using Amazon Athena

6. Created an interactive Power BI dashboard for insights

 Dashboard Insights

Trending category performance

Engagement metrics (views, likes, comments)

Regional and time-based trends

 Tech Stack

AWS S3, Glue, Glue Data Catalog, Lambda, Step Functions, Athena, Power BI, Python, SQL

architecture diagram 

<img width="949" height="711" alt="architectura Diagram_3" src="https://github.com/user-attachments/assets/c129c432-6736-494d-aeea-d8ea4646cecd" />



