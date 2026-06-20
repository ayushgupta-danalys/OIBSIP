# dataset 2 - Play Store User Reviews Sentiment Analysis

## Objective

The aim of this project is to perform sentiment analysis on Google Play Store user reviews by analyzing review text and classifying sentiments into Positive, Negative and Neutral categories.

The project uses Natural Language Processing (NLP) and Machine Learning techniques to understand customer opinions and app feedback.

## Dataset

* Name: Google Play Store User Reviews Dataset
* Source: Kaggle
* File: user_reviews.csv
* Rows: 64295
* Columns: 5

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

* Downloaded Google Play Store User Reviews dataset from Kaggle
* Dataset contains app reviews and sentiment information
* Reviews are categorized as Positive, Negative or Neutral

### 2. Data Exploration and Cleaning

* Checked dataset shape and column names
* Examined data types and missing values
* Removed records with missing reviews or sentiment labels
* Cleaned review text by removing punctuation, numbers and unnecessary characters

### 3. Natural Language Processing (NLP)

* Converted text to lowercase
* Removed punctuation and special characters
* Removed numbers and unwanted text patterns
* Prepared review text for machine learning models

### 4. Feature Engineering

* Applied TF-IDF Vectorization
* Converted text data into numerical features
* Selected important terms from reviews
* Created feature matrix for model training

### 5. Machine Learning Models

* Implemented Naive Bayes Classifier
* Implemented Logistic Regression
* Implemented Support Vector Machine (SVM)
* Compared model performance using accuracy scores

### 6. Data Visualization

* Sentiment Distribution Count Plot
* Model Accuracy Comparison Graph
* Confusion Matrix Heatmap
* Sentiment Percentage Pie Chart
* Review Length Distribution
* Top 10 Apps by Number of Reviews

### 7. Sentiment Prediction

* Built a custom sentiment prediction system
* Tested model on new review samples
* Predicted Positive, Negative or Neutral sentiment

## Key Concepts Implemented

### Sentiment Analysis

* Classified user reviews into Positive, Negative and Neutral categories

### Natural Language Processing (NLP)

* Applied text cleaning and preprocessing techniques

### Machine Learning Algorithms

* Trained and evaluated Naive Bayes, Logistic Regression and SVM models

### Feature Engineering

* Used TF-IDF Vectorization to transform review text into numerical features

### Data Visualization

* Created multiple visualizations to understand sentiment patterns and model performance

## Key Observations

* Positive reviews were the most common sentiment category
* User feedback provides useful insights about app quality
* TF-IDF successfully converted review text into machine learning features
* SVM achieved strong performance for sentiment classification
* Review patterns can help businesses improve user experience

## Files in this Folder

* Play_Store_Sentiment_Analysis.ipynb - main notebook
* screenshots
* README.md - project documentation

## How to Run

1. Install required Python libraries
2. Keep user_reviews.csv in the same folder as notebook
3. Open Play_Store_Sentiment_Analysis.ipynb in Jupyter Notebook
4. Run all cells from top to bottom

## Conclusion

This project successfully performed sentiment analysis on Google Play Store user reviews using NLP and machine learning techniques.

The review text was cleaned, transformed using TF-IDF and classified using multiple machine learning models. The results provide useful insights into customer opinions, user satisfaction and application feedback.
