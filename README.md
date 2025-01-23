# Scalable-ETL-Pipeline-for-E-Commerce-Sales-Data-Using-AWS
To design and implement a scalable ETL pipeline that extracts e-commerce sales data from multiple sources, transforms it into an analytics-ready format, and loads it into an AWS Redshift data warehouse for business intelligence.

Project Description:
•	Extract: Collected raw sales data from multiple sources:
o	Source 1: CSV files stored in an AWS S3 bucket.
o	Source 2: Real-time sales data streamed from an API endpoint.
•	Transform:
o	Cleaned the raw data to handle missing values and outliers using AWS Glue (PySpark).
o	Standardized date formats, normalized product categories, and calculated derived metrics like total sales and profit margins.
o	Partitioned data by date for efficient querying and storage.
•	Load:
o	Loaded the transformed data into an AWS Redshift data warehouse.
o	Optimized Redshift schema by defining appropriate distribution and sort keys to improve query performance.
•	Automation:
o	Automated the pipeline using AWS Lambda and Step Functions to schedule jobs for incremental data updates.
•	Monitoring:
o	Implemented AWS CloudWatch for monitoring pipeline performance and error notifications.
________________________________________
Technologies Used:
•	AWS Services: S3, Glue, Redshift, Lambda, Step Functions, CloudWatch
•	Programming Language: Python (Boto3, PySpark)
•	Database: AWS Redshift
•	Tools: SQL Workbench, AWS CLI
