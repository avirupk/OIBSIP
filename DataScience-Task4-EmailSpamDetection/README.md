# Email Spam Detection with Machine Learning 📧

## OASIS INFOBYTE Data Science Internship

### Task 4 — Email Spam Detection

## 📌 Project Overview

This project focuses on detecting whether a text message is Spam or Ham (legitimate) using Machine Learning and Natural Language Processing (NLP).

The project uses text preprocessing and TF-IDF feature extraction to convert email/message text into numerical features that can be used by Machine Learning classification models.

## 🎯 Objective

The main objective is to build Machine Learning models that can accurately classify messages as:

- Spam
- Ham

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- NLTK
- Jupyter Notebook

## 📊 Dataset

The dataset used in this project is:

`spam.csv`

The dataset contains 5,572 messages with two main fields:

- Label — Spam or Ham
- Message — Text message content

## 🔎 Data Preprocessing

The following preprocessing steps were performed:

1. Load the dataset
2. Select the required columns
3. Rename columns as `Label` and `Message`
4. Inspect the dataset
5. Check for missing values
6. Analyze the distribution of Spam and Ham messages
7. Clean and preprocess the text
8. Remove unnecessary characters
9. Convert text into numerical features

## 📝 NLP Techniques

Natural Language Processing techniques were used for text preprocessing.

The project uses:

- Regular Expressions
- String processing
- NLTK Stopwords
- Porter Stemmer
- TF-IDF Vectorization

## 🤖 Machine Learning Models

The following classification algorithms were used:

- Multinomial Naive Bayes
- Logistic Regression

## 📈 Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Classification Report
- Confusion Matrix

## 📌 Why Recall Matters

Recall is particularly important in spam detection because it measures how many actual spam messages are correctly identified.

A low recall means that many spam messages may be incorrectly classified as legitimate messages.

Therefore, a good spam detection system should aim for strong recall while maintaining good precision.

## 📁 Project Files

```text
DataScience-Task4-EmailSpamDetection/
│
├── Email Spam Detection.ipynb
├── spam.csv
└── README.md
