# Fake News Detection

## Overview
This project aims to build a machine learning model for detecting fake news articles from a dataset containing both fake and true news. Fake news detection is a crucial task in today's information age to ensure the dissemination of accurate information and prevent the spread of misinformation.



## Dataset
The dataset used in this project is from Kaggle which consists of news articles with features like title, text, subject, date, and label. The label represents whether a news article is fake (1) or true (0).

## Methodology
Data Preprocessing: The textual features (title and text) are preprocessed by removing stopwords, special characters, and converting the text to lowercase.

Feature Engineering: The TfidfVectorizer is used to transform the preprocessed text data into numerical vectors, capturing the importance of words in each news article.

Model Training: The transformed data is used to train a Random Forest classifier. Random Forest is an ensemble learning algorithm that combines multiple decision trees for improved accuracy and generalization.

Model Evaluation: The trained model is evaluated on a test set to assess its performance using metrics like accuracy, confusion matrix, and classification report.

## Results
The project provides insights into the performance of the machine learning model in detecting fake news articles. The classification report highlights precision, recall, F1-score, and support for both fake and true news detection.
