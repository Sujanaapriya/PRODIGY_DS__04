# PRODIGY_DS__04
Social Media Sentiment Analysis using Machine Learning

## Project Overview

This project analyzes sentiment patterns in social media data to understand public opinion and attitudes toward various brands and topics.

The project uses Natural Language Processing (NLP) and Machine Learning techniques to classify tweets into:

- Positive
- Negative
- Neutral
- Irrelevant

The objective is to identify public perception, brand reputation, and sentiment trends from large-scale Twitter data.

## Dataset

Dataset: Twitter Entity Sentiment Analysis Dataset

Features:

| Column | Description |
|----------|------------|
| Tweet_ID | Unique Tweet Identifier |
| Entity | Brand/Topic Mentioned |
| Sentiment | Target Label |
| Tweet | Tweet Content |

Total Records: 74,682 Tweets

Sentiment Classes:
- Positive
- Negative
- Neutral
- Irrelevant

Problem Statement

Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes toward specific brands and topics.

---

## Project Workflow

### 1. Data Collection

- Twitter sentiment dataset
- Brand-wise tweet data

  ### 2. Data Preprocessing

- Lowercasing
- URL removal
- Mention removal
- Hashtag removal
- Stopword removal
- Tokenization

### 3. Exploratory Data Analysis

- Sentiment distribution
- Most discussed brands
- Brand-wise sentiment comparison
- Word frequency analysis

### 4. Feature Engineering

**TF-IDF Vectorization

### 5. Machine Learning Models

- Logistic Regression
- Naive Bayes
- Random Forest Classifier

### 6. Model Evaluation

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 7. Visualization
- Sentiment Distribution
- Brand-wise Sentiment Analysis
- Word Clouds
- Model Performance Comparison

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-Learn
- WordCloud

  ## Results

| Model | Accuracy |
|---------|----------|
| Logistic Regression | XX% |
| Naive Bayes | XX% |
| Random Forest | XX% |

Best Performing Model:
Random Forest Classifier

## Key Insights

- Negative sentiment was the most common class.
- Certain brands received significantly higher positive feedback.
- Social media sentiment can provide valuable business intelligence.
- Machine learning effectively classifies public opinions from textual data.


## Future Improvements

- Deep Learning (LSTM)
- BERT-based Sentiment Analysis
- Real-time Twitter Data Analysis
- Dashboard Development

