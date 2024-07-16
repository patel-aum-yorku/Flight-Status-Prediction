# Flight Status Prediction
## Project Overview
This project aims to predict whether a flight will arrive late to its destination. The dataset used contains information on thousands of flights, including details such as departure delays, arrival delays, airlines, airports, and more. The analysis involves exploring the dataset, preprocessing the data, engineering relevant features, and training several machine learning models to predict flight delays.

### Note: Selection of ATL for Model Training
Due to computational constraints and ATL's status as one of the world's busiest airports, this study exclusively trains models on data from Hartsfield-Jackson Atlanta International Airport. This focused approach ensures efficient use of resources while capturing diverse flight scenarios, enhancing the accuracy of our predictive models for flight delays and arrivals.

## Usage Instructions
Exploring the Dataset:

The notebook provides detailed steps to explore and understand the dataset.
Preprocessing the Data:

Data Cleaning: Handle missing values, remove duplicates, and correct data types.
Feature Selection: Identify and select relevant features for the analysis.
Encoding: Convert categorical features to numerical values using techniques like one-hot encoding.
Feature Engineering:

New features are created to improve model performance, such as time-based features, interaction terms, and statistical aggregations.
Model Training and Evaluation:

Models Used: Multiple machine learning models are trained, including:
- Logistic Regression
- kNN
- Random Forest
Evaluation Metrics: Models are evaluated using metrics like accuracy, precision, recall, F1-score, and ROC-AUC.
Hyperparameter Tuning:

Hyperparameters are tuned using techniques like Grid Search and Random Search to find the optimal parameters for each model.
Making Predictions:

Use the trained models to make predictions on new data.

## Disclaimer
Please note that running the entire notebook, including data preprocessing, feature engineering, model training, and evaluation, may take approximately 30 minutes. Ensure you have adequate computational resources and time before starting the execution.
