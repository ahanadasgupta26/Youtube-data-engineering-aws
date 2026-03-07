This project implements an end-to-end data engineering pipeline on AWS to process YouTube trending data. The pipeline ingests raw CSV and JSON data into Amazon S3, transforms the data into optimized Parquet format using AWS Lambda and AWS Glue, and enables analytical querying through Amazon Athena. The curated dataset is then visualized using Power BI by connecting directly to Athena.


## Services Used

Amazon S3 – Data storage for raw and processed datasets  
AWS Lambda – Event-driven transformation of JSON files to Parquet format  
AWS Glue – ETL processing for CSV datasets, schema mapping and Data Catalog management  
Amazon Athena – Serverless SQL querying on data stored in S3  
Power BI – Dashboard and data visualization connected to Athena
