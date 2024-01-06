# TikTok-Review-Sentiment-Analysis

## Overview
This project delves into the sentiment analysis of TikTok app reviews. By employing NLP techniques, the project aims to clean, process, and analyze user reviews to uncover underlying sentiments and visualize them through word clouds.

## Dependencies
- Python
- Pandas
- Matplotlib
- WordCloud
- NLTK

These libraries are used for data manipulation, text processing, sentiment analysis, and visualization.

## Data
The dataset consists of user reviews for the TikTok app, including the review content and user scores. The data is sourced from Google Play reviews.

## Preprocessing
The text data undergoes several preprocessing steps:
- Cleaning: Lowercasing, removing URLs, punctuation, and numbers.
- Tokenization: Splitting text into individual words.
- Stopword Removal: Eliminating common words that add little value.
- Stemming: Reducing words to their root form.

## Model Training and Evaluation
The project employs NLTK's VADER Sentiment Analyzer to assign sentiment scores (positive, negative, neutral) to each review. The analysis does not involve traditional model training but focuses on applying predefined NLP techniques for sentiment analysis.

## Usage
1. Install the required libraries.
2. Load the dataset.
3. Run the script to preprocess the text and perform sentiment analysis.

## Results
The project outputs include:
- A pie chart representing the distribution of user scores.
- Word clouds visualizing common words in positive and negative reviews.
- Sentiment scores for each review, showcasing the distribution of sentiments among the users.

These outputs offer insights into the general sentiment of users towards the TikTok app.

## Note
Ensure you have the dataset (`tiktok_google_play_reviews.csv`) in the correct path to run the script.
