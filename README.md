# 🛍️ Product Review Sentiment Analysis Using NLP

## 📌 Project Overview

This project was developed as part of the Code Alpha Internship.

The objective is to build a Natural Language Processing (NLP) system that analyzes Amazon product reviews and classifies them into three sentiment categories:

- 🟢 Positive
- 🔴 Negative
- 🟡 Neutral

The project uses both a supervised machine learning approach and a lexicon-based sentiment analysis approach.

---

## 🎯 Objectives

- Analyze customer reviews using NLP techniques.
- Classify reviews as Positive, Negative, or Neutral.
- Apply TF-IDF for text feature extraction.
- Train a Logistic Regression classification model.
- Evaluate the model using accuracy, precision, recall, and F1-score.
- Apply VADER, a lexicon-based sentiment analyzer.
- Compare supervised machine learning with lexicon-based sentiment analysis.
- Test the trained model on new reviews.

---

## 📊 Dataset

The project uses the **Amazon Fine Food Reviews** dataset.

The relevant columns used were:

- `Score` — product rating
- `Text` — customer review

### Sentiment Mapping

| Rating | Sentiment |
|---|---|
| 1–2 | Negative |
| 3 | Neutral |
| 4–5 | Positive |

A balanced dataset of **30,000 reviews** was created:

- 10,000 Negative
- 10,000 Neutral
- 10,000 Positive

---

## 🔄 Methodology

```text
Amazon Reviews
       ↓
Sentiment Labeling
       ↓
Dataset Balancing
       ↓
Text Cleaning
       ↓
Train/Test Split
       ↓
TF-IDF Vectorization
       ↓
Logistic Regression
       ↓
Model Evaluation
       ↓
VADER Lexicon Analysis
       ↓
Model Comparison
       ↓
New Review Prediction