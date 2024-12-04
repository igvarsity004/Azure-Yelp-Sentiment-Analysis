# Yelp Review Analysis with Azure Tools

## Project Overview
This project analyzes user-generated reviews from Yelp to gain insights into customer sentiments and business performance. It leverages a variety of Azure tools, including Azure Data Factory, Databricks, and Azure Synapse Analytics, to process, analyze, and visualize the data. The main goal is to predict customer sentiments, identify trends in user behavior, and evaluate the performance of the model.

## Key Components
- **Data Ingestion**: Using **Azure Data Factory** to automate the ingestion of review data from multiple sources like Amazon RDS and Azure Blob Storage.
- **Data Lake**: Data is stored in **Azure Data Lake Storage** for easy management and access.
- **Model Inference**: Using **Databricks** for model inference, where we applied a pre-trained machine learning model to predict sentiment from the reviews.
- **Azure Synapse Analytics**: The results are processed and visualized using **Azure Synapse Analytics**, allowing for detailed analysis of customer behavior across various cities.
- **Machine Learning**: The project utilizes sentiment analysis to predict how customers feel about businesses, and compares the model's predictions against actual sentiments.

## Datasets Used
The following datasets are used in this project:
- **Reviews**: User reviews about businesses.
- **Business**: Details about businesses (e.g., name, location, rating).
- **Check-in**: Information about user check-ins at businesses.
- **Tips**: Tips shared by users about businesses.
- **Users**: Information about users interacting with Yelp.

## Setup and Execution

### Prerequisites
Before running this project, ensure that you have access to the following:
- **Azure Subscription**: For using Azure Data Factory, Databricks, and Azure Synapse Analytics.
- **Databricks Workspace**: Used for data processing and model inference.
- **Azure Synapse Analytics**: For querying and visualizing the results.


