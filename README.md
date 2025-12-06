# order_transaction_analytics
Order transaction analytics on Databricks project leveraging the next tech stack: 
s3 - To host Raw CSV files and Images
delta tables - Create Delta tables from the files on s3 to generate a medallion architecture
lakehouse connect - To connect to sql server on AWS RDS
lakehouse connect with fivetran - To connect to postrgres on AWS RDS
lakehouse connect with fivetran - To connect to MongoDB Atlas
Genie - To perfrom comprenhnsive and easy data exploration on the Gold Layer
Databricks Dashboards - To display data from delta tables
Spark with pyspark - To transform data from Raw Volumes on CSV to Gold Layer
Databricks Jobs and Pipelines - To automatically transform data form Raw to Gold Layer
