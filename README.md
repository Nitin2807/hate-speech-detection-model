# Hate Speech Detection from Tweets

This project aims to classify tweets into three categories: hate speech, offensive language, or neutral language.

## Project Overview

The notebook processes a dataset of labeled tweets to train a machine learning model for hate speech detection. The key steps include:
- **Data Loading:** The project starts by loading the `labeled_data.csv` file.
- **Data Cleaning and Preprocessing:** Text data from the tweets is cleaned by:
    - Converting to lowercase.
    - Removing URLs, user mentions, hashtags, punctuation, numbers, and common English stop words.
- **Model Training:** A Decision Tree Classifier is trained on the cleaned text data.
- **Evaluation:** The model's performance is evaluated using a confusion matrix and an accuracy score, achieving an accuracy of approximately 86.5%.

## How to Use
1. Clone the repository.
2. Ensure you have the required libraries like pandas, numpy, nltk, and scikit-learn installed.
3. Run the Jupyter notebook `hate_speech.ipynb`.
