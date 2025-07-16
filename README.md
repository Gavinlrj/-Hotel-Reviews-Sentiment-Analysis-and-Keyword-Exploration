# Hotel Review Sentiment Analysis and Aspect Extraction

A comprehensive NLP-based solution for classifying sentiment, extracting key aspects, and analyzing customer feedback in hotel reviews.

## Project Objective

This project aims to leverage a range of Natural Language Processing (NLP) and Machine Learning methods to analyze hotel reviews, automatically classify sentiment (positive/negative), and extract important aspects mentioned by customers. The end goal is to provide actionable insights for hotel service improvement and customer satisfaction management.

## Features

- **Data Cleaning & Preprocessing:**  
  Text normalization (lowercase, punctuation removal, tokenization, stop-word removal, lemmatization).
- **Exploratory Data Analysis:**  
  Visualizes rating distribution, word counts, and key predictive words for positive/negative sentiment.
- **Modeling Approaches:**  
  - **Lexicon-Based:** VADER sentiment analyzer.
  - **Machine Learning:** Multinomial Naive Bayes, Logistic Regression, SVM with TF-IDF features.
  - **Combined Approach:** SVM + VADER features for improved accuracy.
- **Aspect Extraction:**  
  Identifies and analyzes review content by service aspect (e.g., location, cleanliness, staff).
- **Evaluation:**  
  Reports accuracy, precision, recall, F1-score for each model; compares lexicon and machine learning methods.
- **Visualization:**  
  Rating distributions, word count relationships, model comparison.
