# Yelp Review Sentiment Analysis

## Project Overview
This project utilizes Azure tools to analyze **Yelp user reviews** and predict customer sentiment. The goal is to extract valuable insights from user feedback to help businesses understand customer experiences and improve their performance. The data pipeline integrates **Azure Data Factory**, **Databricks**, **Azure Synapse Analytics**, and **Azure Data Lake Storage** to process, analyze, and visualize review data efficiently.

The key components of the project include:
- **Data Ingestion**: Automating data collection from various sources using **Azure Data Factory**.
- **Data Processing**: Using **Databricks** to preprocess and train a machine learning model on Yelp review data.
- **Model Inference**: Applying the trained model to predict customer sentiment and ratings.
- **Data Visualization**: Using **Azure Synapse Analytics** to visualize results and draw insights.

### Key Features
- **Sentiment Analysis**: Predicting user sentiments based on the content of Yelp reviews.
- **City-based Analysis**: Understanding review trends by analyzing data across cities.
- **Model Evaluation**: Comparing the predictions made by the machine learning model with actual sentiments.
- **Automated Data Pipelines**: Automated workflows to retrieve and process data regularly.

### Tools & Technologies Used
- **Azure Data Factory (ADF)**: For data ingestion and ETL pipelines.
- **Azure Databricks**: For data processing, model training, and inference using Spark.
- **Azure Synapse Analytics**: For querying data and generating visualizations.
- **Azure Data Lake Storage**: For storing raw and processed datasets.
- **Machine Learning**: Sentiment analysis using machine learning models.

---

## Datasets
The following datasets are used in this project:
1. **Reviews Dataset**: Contains user reviews about businesses on Yelp.
2. **Business Dataset**: Includes information about businesses (name, location, ratings).
3. **Check-ins Dataset**: Records user check-ins at different businesses.
4. **Tips Dataset**: User-generated tips about businesses.
5. **Users Dataset**: Information about Yelp users (user_id, profile data).

---

## Setup & Installation

### Prerequisites
- **Azure Subscription**: Required to set up the services (Azure Data Factory, Databricks, Azure Synapse, and Data Lake).
- **Databricks Workspace**: For processing and running machine learning models.
- **Azure Synapse Analytics**: For querying and analyzing the data.
- **Python Libraries**: Install required libraries in Databricks (e.g., PySpark, MLlib).




