# SENTIMATEANYLSIS
📊 Sentiment Analysis of Alexa Reviews
📌 Overview

This project performs sentiment analysis on customer reviews of Amazon Alexa products.
The dataset contains reviews, ratings, and feedback labels (positive / negative).
Using Natural Language Processing (NLP) techniques and Machine Learning models, we predict whether a review expresses positive or negative sentiment.

📂 Dataset

Source: Amazon Alexa Reviews Dataset (Kaggle)

Features:

rating → numeric rating (1–5)

verified_reviews → text of the review

feedback → sentiment label (1 = positive, 0 = negative)

⚙️ Project Workflow

Data Preprocessing

Removed stopwords, punctuation, and special characters

Tokenized and vectorized text using TF-IDF

Handled class imbalance

Exploratory Data Analysis (EDA)

Distribution of positive vs. negative reviews

Word clouds for positive/negative reviews

Review length analysis

Modeling

Built machine learning pipelines with:

Logistic Regression

Naïve Bayes

Random Forest

Support Vector Machine (SVM)

Evaluated using accuracy, precision, recall, F1-score
