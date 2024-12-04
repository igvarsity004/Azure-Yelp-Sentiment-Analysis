# Yelp Review Sentiment Analysis

## Project Overview
This project uses Azure tools to analyze Yelp user reviews and predict customer sentiment. The goal is to extract insights from customer feedback to help businesses improve their services and customer satisfaction. We use **Azure Data Factory**, **Databricks**, **Azure Synapse Analytics**, and **Azure Data Lake** to process and analyze large datasets from Yelp reviews.

## Key Features & Technologies:
- **Data Ingestion**: Using **Azure Data Factory** to pull data from Amazon RDS and Blob Storage.
- **Sentiment Analysis**: Applied machine learning models in **Databricks** for sentiment prediction based on review text.
- **Data Storage**: Leveraged **Azure Data Lake** for efficient data storage and management.
- **Real-Time Analytics**: Used **Azure Synapse Analytics** for querying and visualizing the data.

## Setup & Installation

1. **Azure Data Factory**:
   - Set up **weekly** and **daily pipelines** to ingest data from Amazon RDS and Blob Storage.
   - Ensure the pipelines are set to trigger automatically.

2. **Databricks**:
   - Create a **Databricks workspace** and upload the datasets.
   - Run the Databricks notebooks to preprocess data and apply machine learning for sentiment analysis.

3. **Azure Synapse Analytics**:
   - Link **Azure Synapse** to **Azure Data Lake Storage** and create external tables to query and analyze the data.

##



