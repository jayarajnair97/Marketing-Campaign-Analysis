# Marketing Campaign Analysis
## Introduction
The marketing campaign analysis aims to predict whether customers will respond positively or negatively to a marketing campaign. This analysis is vital for businesses to optimize their marketing strategies and allocate resources effectively. In this project, we analyze various features of customers to predict their response to marketing campaigns.

## Data
The dataset used for this analysis contains information about a marketing campaign, including details about customers and their responses. The dataset includes features such as:
Age
Income
Marital status
Education
Previous marketing campaign responses
The dataset is preprocessed to handle missing values and categorical features.

## Tools and Techniques Used
Python Libraries:
Pandas, NumPy for data manipulation
Matplotlib, Seaborn for data visualization
Scikit-learn for machine learning models
TensorFlow and Keras for deep learning models
Streamlit for building the web application

## Data Preprocessing
Missing values in the 'Income' column are imputed with the mean value.
Categorical features are one-hot encoded.
Exploratory Data Analysis (EDA)
Correlation heatmap is used to understand the relationships between different features.
Histograms and pie charts are used to visualize the distribution of the target variable and other important features.

## Model Selection
Logistic Regression:
GridSearchCV is used to find the best hyperparameters.
Support Vector Classification (SVC):
GridSearchCV is used to find the best hyperparameters.
Random Forest:
GridSearchCV is used to find the best hyperparameters.
XGBoost:
GridSearchCV is used to find the best hyperparameters.
Deep Neural Network (DNN):
A simple DNN model is defined using TensorFlow and Keras.

## Model Evaluation
Train and test splits are performed.
Standardization is applied using StandardScaler.
Models are evaluated using classification_report.
Cross-validation scores are calculated.

## Model Deployment
A Streamlit web application is built to deploy the trained models.
Users can upload a CSV file containing customer data.
The selected model makes predictions on the uploaded data.
Predictions are displayed to the user.
## Conclusion
This project provides a comprehensive analysis of marketing campaign data, including data preprocessing, EDA, model selection, evaluation, and deployment. The Streamlit web application allows users to make predictions on their own data, helping businesses optimize their marketing strategies.
