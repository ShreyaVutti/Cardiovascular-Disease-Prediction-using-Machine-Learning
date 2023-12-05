# Cardiovascular-Disease-Prediction-using-Machine-Learning
Overview
Cardiovascular diseases (CVD) are a leading cause of morbidity and mortality worldwide. Early detection and prediction of CVD can significantly impact patient outcomes. This repository contains a Python-based machine learning model that predicts the likelihood of cardiovascular disease based on various input features.

Dataset
The dataset used for training and testing the model includes information on age, gender, cholesterol levels, glucose levels, smoking habits, alcohol consumption, physical activity, body mass index (BMI), and blood pressure. The dataset underwent thorough preprocessing to ensure data quality and suitability for machine learning algorithms.

Methods
1. Data Preprocessing
The dataset was preprocessed to handle missing values, encode categorical variables, and scale numerical features. This step ensures the dataset is ready for training and testing machine learning models.

2. Data Analysis and Visualization
Exploratory Data Analysis (EDA) was performed to gain insights into feature distributions and relationships. Visualization techniques, such as histograms, box plots, and correlation matrices, were employed to better understand the dataset.

3. Correlation Matrix
A correlation matrix was generated to identify relationships between different features, aiding in feature selection and model performance optimization.

4. Machine Learning Models
The following machine learning models were implemented:

Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
Logistic Regression
These models were chosen for their effectiveness in handling classification tasks, such as predicting the presence or absence of cardiovascular disease.

5. Model Evaluation
The models were evaluated using metrics such as accuracy, precision, recall, and F1 score. Cross-validation techniques were employed to ensure robustness and avoid overfitting.

Usage
To predict cardiovascular disease for a specific individual, provide input features (age, gender, cholesterol, glucose, smoking, alcohol, activity, BMI, blood pressure) in the input_data array within the provided Python script. The model will output a prediction of 0 (no cardiovascular disease) or 1 (presence of cardiovascular disease).Results
The model's predictive capabilities are demonstrated in the provided Python script. Users can interpret the output to determine the likelihood of cardiovascular disease based on the input features.

Conclusion
This project provides a practical tool for predicting cardiovascular disease using machine learning. Users can leverage the implemented models to assess the risk of CVD based on individual characteristics. Continuous updates and improvements to the model may enhance its performance in diverse populations and datasets.
