## 📰 Misinformation Detection using Machine Learning

Fake News Detection System using Machine Learning, NLP, TF-IDF, Sentiment Analysis, and Logistic Regression.

## 📖 Overview

Misinformation spread through digital media has become a major challenge in today’s world. This project aims to automatically classify news articles as Real or Fake using Machine Learning and Natural Language Processing (NLP) techniques.

## The project uses the GossipCop Dataset and applies:

- Text preprocessing
- TF-IDF feature extraction
- Sentiment analysis
- Readability analysis
- Logistic Regression classification

The model learns textual patterns and writing styles commonly found in fake and real news articles.

## ✨ Key Features

- Fake News Detection using ML
- NLP-based text preprocessing
- TF-IDF Vectorization
- Sentiment Analysis using VADER
- Readability & stylistic feature extraction
- Logistic Regression Classifier
- Confusion Matrix & Classification Report
- Learning Curve Visualization


## 🛠️ Tech Stack
- Technology	Purpose
- Python	Programming Language
- Pandas	Data Manipulation
- NumPy	Numerical Operations
- Scikit-learn	Machine Learning
- NLTK	NLP Processing
- TextStat	Readability Analysis
- Matplotlib	Data Visualization
- Joblib	Model Saving

## 📂 Dataset

The project uses the GossipCop Fake News Dataset:

- gossipcop_real.csv → Real News Articles
- gossipcop_fake.csv → Fake News Articles
- Dataset Preparation
Merged both datasets
Assigned labels:
1 → Real News
0 → Fake News
Removed null values
Shuffled data for unbiased training

## ⚙️ Project Workflow
Data Collection
       ↓
Data Cleaning & Preprocessing
       ↓
Feature Extraction (TF-IDF + NLP Features)
       ↓
Model Training (Logistic Regression)
       ↓
Model Evaluation
       ↓
Prediction of Fake / Real News

## 🧹 Data Preprocessing

The following preprocessing techniques were applied:

Lowercase conversion
Removal of punctuation & special characters
Stopword handling
Text cleaning
Missing value removal

## 🧠 Feature Engineering
🔹 TF-IDF Vectorization

Converts text into numerical feature vectors.

🔹 Additional Features
Sentiment Scores
Readability Metrics
Stylistic Features

## 🤖 Machine Learning Model
Logistic Regression

The project uses Logistic Regression for binary classification.

## 📊 Model Evaluation

The model performance was evaluated using:

Accuracy Score
Precision
Recall
F1-Score
Confusion Matrix
Classification Report
Learning Curve

## 📈 Output

The model predicts whether a news article is:

✅ Real News
❌ Fake News

The project also visualizes:

Learning Curves
Model Accuracy
Confusion Matrix
Classification Metrics

## 🚀 Future Enhancements
Implement Deep Learning Models (LSTM, BiLSTM)
Use Transformer Models like BERT
Build a Web Application Interface
Add Real-time Fake News Detection
Support Multiple Languages
