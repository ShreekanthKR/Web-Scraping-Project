Amazon Reviews Sentiment Analysis

Overview

This project performs Sentiment Analysis on Amazon Reviews using NLP techniques. It includes web scraping, text preprocessing, and machine learning to classify reviews as positive or negative.

Features

Reads and preprocesses Amazon review data.

Cleans text by removing stopwords.

Generates Word Clouds for visualization.

Converts text into numerical representation using TF-IDF Vectorization.

Splits data into training and testing sets.

Implements Logistic Regression for sentiment classification.

Evaluates model accuracy and displays a confusion matrix.

Installation & Setup

Prerequisites

Ensure you have Python installed and install required dependencies:

pip install pandas numpy scikit-learn nltk matplotlib wordcloud

Run the Script

python sentiment_analysis.py

Folder Structure

📂 Amazon-Reviews-Sentiment  
 ┣ 📜 sentiment_analysis.py   # Main Python script  
 ┣ 📜 AmazonReview.csv        # Dataset  
 ┣ 📜 README.md               # Documentation  
 ┣ 📜 requirements.txt        # List of dependencies  

Usage

Ensure you have the dataset AmazonReview.csv in the project folder.

Run sentiment_analysis.py to process reviews and classify sentiments.

The script will generate Word Clouds for both positive and negative reviews.

The model will be trained and tested using Logistic Regression.

The accuracy score and confusion matrix will be displayed.


Technologies Used

Python

Pandas

NLTK

Scikit-learn

Matplotlib

WordCloud
