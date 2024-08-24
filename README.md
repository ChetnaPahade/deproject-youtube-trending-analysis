# deproject-youtube-trending-analysis

## Introduction
Efficiently manage and analyze YouTube video data, focusing on category-based trends and security. Streamline workflows for valuable insights.

## Project Goals
### Data Ingestion — Develop a mechanism to ingest data from various sources.
### ETL System — Transform raw data into a suitable format for use.
### Data Lake — Establish a centralized repository for storing data from multiple sources.
#### Scalability — Ensure the system can scale with increasing data volume.
Cloud — Leverage AWS for processing large datasets, avoiding local limitations.
Reporting — Create a dashboard to answer key questions identified earlier.

## Services We Will Be Using
Amazon S3: A scalable object storage service offering high data availability, security, and performance.
AWS IAM: Identity and Access Management service that securely manages access to AWS resources and services.
Amazon QuickSight: A scalable, serverless business intelligence (BI) service with machine learning capabilities, designed for the cloud.
AWS Glue: A serverless data integration service that simplifies the process of discovering, preparing, and combining data for analytics and machine learning.
AWS Lambda: A compute service that allows code execution without the need to manage servers.
AWS Athena: An interactive query service for S3, enabling data analysis directly in S3 without the need for data loading.

## Dataset Used
Kaggle Dataset: Daily trending YouTube videos data across multiple regions. Includes video details, views, likes, dislikes, comments, and category IDs. CSV format for structured data.

https://www.kaggle.com/datasets/datasnaek/youtube-new

## Architecture Diagram
<img src="architecture.jpeg">

## Guidance from:
https://youtu.be/yZKJFKu49Dk
