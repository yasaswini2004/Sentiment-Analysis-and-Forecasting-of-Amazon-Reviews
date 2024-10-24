# Sentiment-Analysis-and-Forecasting-of-Amazon-Reviews
# Project Overview
This project performs sentiment analysis on Amazon reviews using VADER, detects anomalies in sentiment trends, and forecasts future sentiment using ARIMA. The project also builds a predictive model using Random Forest and explains feature importance with SHAP.

# Dataset
Get the dataset from here: https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews

# Features
Data Preprocessing: Cleans raw data, converts Unix timestamps to human-readable dates.
SQL Integration: Stores the dataset in SQLite and executes queries to analyze the data.
Sentiment Analysis: Analyzes sentiment scores for each review using the VADER lexicon.
Anomaly Detection: Detects outliers in sentiment using Z-scores.
Visualization: Visualizes sentiment trends and review score distributions.
Time Series Forecasting: Uses ARIMA for predicting future sentiment.
Random Forest Prediction: Predicts sentiment using Random Forest with hyperparameter tuning.
SHAP Interpretation: Provides insights into the model's predictions using SHAP.
# Technologies Used
Pandas: Data manipulation
NLTK: Sentiment analysis (VADER)
Matplotlib: Data visualization
Plotly: Interactive visualizations
SQLite: In-memory database for SQL operations
Scikit-learn: Machine learning model (Random Forest)
SHAP: Model interpretability
ARIMA: Time-series forecasting

# How to Use the Code
Data Preprocessing: Load the dataset and clean it using Pandas.
SQL Queries: Use SQLite to run SQL queries to explore the data.
Sentiment Analysis: Add sentiment scores to the data using VADER.
Modeling: Build a time-series forecasting model with ARIMA and predict sentiment using Random Forest.
Visualization: Create interactive and static plots to visualize the analysis.

# Future Improvements
Implement advanced sentiment models (e.g., transformers like BERT).
Scale the solution using cloud databases for larger datasets.
Deploy the model for real-time sentiment analysis.

# Contributing
Feel free to fork this repository and create pull requests. For any issues or suggestions, open a new issue.

# License
This project is licensed under the MIT License.
