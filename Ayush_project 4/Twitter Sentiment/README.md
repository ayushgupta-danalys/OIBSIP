# Dataset 1 - Twitter Sentiment Analysis

## Objective

The aim of this project is to perform sentiment analysis
on Twitter data by analyzing tweet text and classifying
sentiments into Positive, Negative and Neutral categories.
The project uses Natural Language Processing (NLP) and
Machine Learning techniques to understand public opinion
and social media trends.

## Dataset

* Name: Twitter Sentiment Dataset
* Source: Kaggle
* File: Twitter_Data.csv
* Rows: 162980+
* Columns: 2

## Tools and Libraries Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

## Steps Performed

### 1. Data Collection

* Downloaded Twitter sentiment dataset from Kaggle
* Dataset contains tweet text and sentiment labels
* Sentiment labels include Positive, Negative and Neutral

### 2. Data Exploration and Cleaning

* Checked dataset shape and column names
* Checked data types and missing values
* Removed records containing missing values
* Converted sentiment labels into readable categories
* Cleaned tweet text by removing punctuation,
  numbers and unnecessary characters

### 3. Natural Language Processing (NLP)

* Converted text to lowercase
* Removed unwanted symbols and punctuation
* Applied text preprocessing techniques
* Prepared text data for machine learning models

### 4. Feature Engineering

* Applied TF-IDF Vectorization
* Converted text into numerical features
* Selected important words and terms for analysis
* Prepared feature matrix for model training

### 5. Machine Learning Models

* Implemented Naive Bayes Classifier
* Implemented Logistic Regression
* Implemented Support Vector Machine (SVM)
* Compared model performance using accuracy scores

### 6. Data Visualization

* Sentiment distribution count plot
* Model accuracy comparison graph
* Confusion matrix heatmap
* Sentiment percentage pie chart
* Tweet length distribution histogram

### 7. Sentiment Prediction

* Built a custom prediction system
* Tested model on new tweet samples
* Predicted Positive, Negative or Neutral sentiment

## Key Concepts Implemented

### Sentiment Analysis

* Classified tweets into Positive, Negative and Neutral sentiments

### Natural Language Processing (NLP)

* Applied text cleaning and preprocessing techniques

### Machine Learning Algorithms

* Trained and evaluated Naive Bayes, Logistic Regression and SVM models

### Feature Engineering

* Used TF-IDF to convert text data into numerical features

### Data Visualization

* Created multiple visualizations for better understanding of sentiment patterns

## Key Observations

* Positive tweets were the most common sentiment category
* TF-IDF successfully transformed text into useful features
* SVM achieved the highest classification performance
* Machine learning models effectively identified sentiment patterns
* Visualizations helped understand sentiment distribution clearly

## Files in this Folder

* Twitter_Sentiment_Analysis.ipynb - main notebook
* screenshots
* README.md - project documentation

## How to Run

1. Install required Python libraries
2. Keep Twitter_Data.csv in the same folder as notebook
3. Open Twitter_Sentiment_Analysis.ipynb in Jupyter Notebook
4. Run all cells from top to bottom

## Conclusion

This project successfully performed sentiment analysis
on Twitter data using NLP and machine learning techniques.
The text data was cleaned, transformed using TF-IDF and
classified using multiple machine learning models. The
results provide insights into public opinion and sentiment
patterns expressed on social media platforms.
