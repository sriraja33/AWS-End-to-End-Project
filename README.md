# AWS-End-to-End-Project
## Introduction
This project demonstrates an end-to-end AWS data pipeline architecture. It leverages Amazon S3 (via S3 APIs) for scalable data ingestion and storage, AWS Glue and Lambda for ETL and transformation orchestration, Amazon Athena for serverless querying, Amazon Redshift as the analytical data warehouse, and Amazon QuickSight for interactive data visualization and business intelligence reporting.

## Data Architecture
![Data Architecture.jpg](https://github.com/sriraja33/AWS-End-to-End-Project/blob/main/Data%20Architecture.jpg)

## Technology & Services Used

1. Programming Language - Python
2. Scripting Langugae - SQL
3. AWS S3
4. AWS Glue
5. AWS Glue Catalog
6. AWS Lambda
7. AWS Identity & Access Management
8. AWS Athena
9. AWS Redshift
10. AWS SageMaker
11. AWS QuickSight

## Dataset Used

This Kaggle dataset contains statistics (CSV files) on daily popular YouTube videos over the course of many months. There are up to 200 trending videos published every day for many locations. The data for each region is in its own file. The video title, channel title, publication time, tags, views, likes and dislikes, description, and comment count are among the items included in the data. A category_id field, which differs by area, is also included in the JSON file linked to the region.

https://www.kaggle.com/datasets/datasnaek/youtube-new

## Scripts for the Project

1) [S3-Command Line Interface](https://github.com/sriraja33/AWS-End-to-End-Project/blob/main/CLI%20commands.txt)
2) [Lambda Function for Transformation](https://github.com/sriraja33/AWS-End-to-End-Project/blob/main/lambda_function.ipynb)
3) [Pyspark Code for Transformation](https://github.com/sriraja33/AWS-End-to-End-Project/blob/main/pyspark_code.ipynb)
