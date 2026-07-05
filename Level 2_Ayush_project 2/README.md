# Wine Quality Prediction using Machine Learning

This repository contains a Machine Learning project that predicts wine quality using different chemical properties of wine. The project demonstrates the complete machine learning workflow, including data exploration, preprocessing, model training, evaluation, comparison of multiple classification models, and visualization using Python and Scikit-learn.

## Project Objective

Build machine learning models to predict wine quality based on its chemical characteristics. The project provides practical experience in data preprocessing, feature selection, model training, evaluation, visualization, and comparing multiple classification algorithms.

## Project Workflow

### 1. Data Collection

* Load the Wine Quality dataset
* Explore the dataset structure

### 2. Data Exploration and Cleaning

* Display dataset information
* Check dataset shape
* View summary statistics
* Check missing values
* Check duplicate records
* Remove unnecessary columns
* Analyze data types

### 3. Feature Selection

* Select relevant chemical properties as input features
* Define the target variable (Wine Quality)

### 4. Data Preprocessing

* Split the dataset into training and testing sets
* Apply feature scaling using StandardScaler where required

### 5. Model Training

Train and compare the following machine learning models:

* Random Forest Classifier
* Stochastic Gradient Descent (SGD) Classifier
* Support Vector Classifier (SVC)

### 6. Model Evaluation

Evaluate each model using:

* Accuracy Score
* Confusion Matrix
* Classification Report

### 7. Data Visualization

* Wine Quality Distribution
* Correlation Heatmap
* Confusion Matrix Visualization
* Feature Importance (Random Forest)

### 8. Model Comparison

* Compare the accuracy of all three classification models
* Identify the best-performing model

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Key Concepts Covered

* Classification Algorithms
* Random Forest Classifier
* SGD Classifier
* Support Vector Classifier (SVC)
* Data Exploration
* Data Cleaning
* Feature Selection
* Feature Scaling
* Train-Test Split
* Model Training
* Model Evaluation
* Data Visualization
* Model Comparison

## Project Files


Wine-Quality-Prediction/
│
├── Wine_Quality_Prediction.ipynb
├── WineQT.csv
├── README.md
└── screenshots/

## Results

Three different machine learning classification models were trained and evaluated using the Wine Quality dataset. Their performance was measured using Accuracy Score, Confusion Matrix, and Classification Report. Finally, the models were compared to identify the best-performing classifier for predicting wine quality.

## Conclusion

This project demonstrates the implementation and comparison of three machine learning classification algorithms for wine quality prediction. It covers the complete machine learning workflow from data collection and preprocessing to model evaluation, visualization, and performance comparison, providing practical experience with supervised machine learning using Scikit-learn.
