# Sentiment-analysis-using-Mongodb
Sentiment Analysis using MongoDB
This project is focused on performing sentiment analysis on the Sentiment140 dataset using MongoDB for data storage and analysis. The project is divided into two main files: ETL (Extract, Transform, Load) and Prediction.

# Dataset
The Sentiment140 dataset from Kaggle contains a collection of tweets labeled with sentiment (positive or negative). The dataset serves as the foundation for sentiment analysis in this project.

# Files
1. ETL File
 
Purpose: Extracts data from the Sentiment140 dataset, transforms it by cleaning and organizing, drops unnecessary columns, and loads the processed data into MongoDB Atlas.

Usage: Run this file to perform the ETL process and set up the data in MongoDB for analysis.

2. Prediction File

Purpose: Preprocesses the data and utilizes an LSTM (Long Short-Term Memory) model for sentiment prediction.

Usage: Execute this file to preprocess the data, train the LSTM model, and perform sentiment analysis predictions.

# Requirements
Python 

MongoDB-ATLAS/Compass

Tenforflow

keras

# Usage

Setting Up MongoDB Atlas

Create an account on MongoDB Atlas.

Configure your connection string and credentials in the ETL file to enable data loading into MongoDB.

ETL Process

Run the ETL file to extract, transform, and load the Sentiment140 dataset into MongoDB Atlas.

Sentiment Prediction

Execute the Prediction file to preprocess the data and utilize the LSTM model for sentiment analysis.
