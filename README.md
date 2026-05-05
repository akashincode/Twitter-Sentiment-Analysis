# Twitter Sentiment Analysis

An NLP project to classify tweets into **Positive / Negative / Neutral** sentiment using classical ML models and a small LSTM.

**Owner:** Akash Adhikary

---

## Overview

This project compares TF-IDF-based classifiers (Logistic Regression, Naive Bayes, SVM) against a Keras LSTM on the Tweet Sentiment Extraction dataset, with extensive EDA and word cloud visualizations.

**Dataset:** [Tweet Eval — Sentiment (Hugging Face)](https://huggingface.co/datasets/tweet_eval)

---

## Project Structure

```
├── Twitter_Sentiment_Analysis.ipynb   # Main notebook
└── README.md
```

---

## Pipeline

1. Setup & Imports
2. Load Dataset (Hugging Face)
3. EDA — Class Balance, Tweet Length, Word Frequency, N-grams
4. Multivariate Analysis
5. Word Clouds per Sentiment Class
6. Text Cleaning & Lemmatization
7. TF-IDF + Logistic Regression (baseline)
8. TF-IDF + Multinomial Naive Bayes
9. TF-IDF + Linear SVM
10. Small LSTM (Keras)
11. Comparative Evaluation

---

## Tech Stack

`TensorFlow` · `Keras` · `scikit-learn` · `NLTK` · `HuggingFace Datasets` · `WordCloud` · `Plotly`

---

## How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Run all cells sequentially
3. No Kaggle credentials needed — dataset loads via Hugging Face
