YouTube Data Engineering & Analytics Project

📘 Overview
This project demonstrates the end-to-end process of building a scalable data engineering pipeline to analyze YouTube trending videos. It covers everything from data ingestion and transformation to cloud storage and visual reporting, all designed to handle large datasets efficiently.

🎯 Project Goals
Data Ingestion – Bring in video data from multiple file-based sources.

ETL Pipeline – Clean and transform raw data into structured formats ready for analysis.

Data Lake Architecture – Maintain a centralized storage system to handle structured and semi-structured data.

Scalability – Design the solution to handle growth in data volume over time.

Cloud Integration – Use cloud-native tools to process and store large datasets reliably.

Data Visualization – Build dashboards to generate insights and answer key questions from the data.

☁️ AWS Services Utilized
Amazon S3 – Stores raw and processed data files in a scalable object storage environment.

AWS IAM – Manages access permissions and ensures secure interactions between services.

Amazon QuickSight – Used to build interactive dashboards and visualize trends from processed data.

AWS Glue – Performs automated data discovery, cleaning, and transformation in a serverless environment.

AWS Lambda – Handles event-driven processing tasks without needing dedicated infrastructure.

Amazon Athena – Allows for SQL-like querying directly on data stored in S3.

📊 Dataset Description
The dataset contains information on YouTube’s trending videos across multiple countries. It includes metrics such as:

Video title and channel

Publish date and time

Tags and categories

Views, likes, dislikes, and comment counts

Description and metadata

Each region's data is stored in separate CSV files, and there's a mapping JSON file for category IDs.

🔗 Link to Dataset on Kaggle
