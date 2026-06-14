# Twitter Sentiment Analysis using Machine Learning

## Project Overview

This project is a Machine Learning-based Sentiment Analysis system that classifies Twitter posts into three sentiment categories:

- Positive 😊
- Neutral 😐
- Negative 😞

The model analyzes tweet text and predicts the sentiment using Natural Language Processing (NLP) techniques and Machine Learning algorithms.

---

## Dataset

Dataset: Twitter Sentiment Dataset

Total Records: 162,980 Tweets

Sentiment Labels:

- 1 = Positive
- 0 = Neutral
- -1 = Negative

---

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-Learn
- TF-IDF Vectorization
- Logistic Regression
- Support Vector Machine (SVM)
- Matplotlib
- Pickle

---

## Project Workflow

### 1. Data Preprocessing

- Remove special characters
- Convert text to lowercase
- Remove stopwords
- Apply lemmatization using WordNetLemmatizer

### 2. Feature Extraction

- TF-IDF Vectorization
- Maximum Features: 5000

### 3. Model Training

#### Logistic Regression

- Accuracy: 84.57%

#### Support Vector Machine (SVM)

- Accuracy: 85.35%

### 4. Model Evaluation

- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix

### 5. Model Saving

The trained model and vectorizer are saved using Pickle:

- twitter_sentiment_model.pkl
- twitter_tfidf.pkl

---

## Sample Predictions

| Tweet | Prediction |
|---------|-----------|
| Awesome work | Positive |
| I hate this | Negative |
| I went to college today | Neutral |

---

## Files Included

- twitter.ipynb
- Twitter_Data.csv
- twitter_sentiment_model.pkl
- twitter_tfidf.pkl
- README.md

---

## Future Improvements

- Deep Learning Models (LSTM/BERT)
- Web Application Deployment
- Real-Time Twitter Sentiment Analysis
- Interactive Dashboard

---

## Author

Gopika

Machine Learning Internship Project
