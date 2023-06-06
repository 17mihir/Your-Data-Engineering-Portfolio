# Stackfolio's Data Engineer & Data Streaming Projects I worked on
My Portfolio of all the projects I did for both my Udacity Data Engineer and Data Streaming Nanodegrees

Stackfolio's Data Engineer Capstone Project
The purpose of this project is to build an ETL pipeline that will be able to provide information to data analysts, immigration and climate researchers etc with temperature, population and immigration statistics for different cities. It does this by first extracting temperature, airport, immigration and demographic data from various datasets, perform some transformation on it and convert the data into json files using Apache Spark that can be then uploaded to a Redshift database. Using Apache Airflow, the json files get migrated to s3, then the data gets uploaded to Redshift, undergoes further transformation and gets loaded to normalized fact and dimension tables using a series of reusable tasks that allow for easy backfills. Finally, data checks are run against the data in the fact and dimension tables so as to catch any discrepancies that might be found in the data.
UDEND Sparkify Data Pipeline Project with Apache Airflow
The purpose of this project was to build a dynamic ETL data pipeline that utilizes automation and monitoring. The data pipeline is built from reusable tasks allows for easy backfills. It utilizes custom operators to perform tasks such as staging the data, filling the data warehouse, and running a check on the data as the final step so as to to catch any discrepancies in the datasets.
Sparkify Data Warehouse Project for song play analysis
The purpose of this project is to build an ETL pipeline that will be able to extract song data from an S3 bucket and transform that data to make it suitable for analysis. This data can be used with business intelligence and visualization apps that will help the analytics team to better understand what songs are commonly listened to on the app.
UDEND Sparkify Data Lake Project with Apache Spark
The purpose of this project was to build an ETL pipeline that will be able to extract song and log data from an S3 bucket, process the data using Spark and load the data back into s3 as a set of dimensional tables in spark parquet files. This helps analysts to continue finding insights on what their users are listening to.
Spark Streaming Project
The purpose of this project was to create a Kafka server to produce data and ingest data through Spark Structured Streaming.
Public Transit Status with Apache Kafka
In this project, I constructed a streaming event pipeline around Apache Kafka and its ecosystem. Using public data from the Chicago Transit Authority I built an event pipeline around Kafka that allows me to simulate and display the status of train lines in real time.
