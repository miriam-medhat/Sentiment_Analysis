# Sentiment_Analysis

## 📁 Project Overview

This project performs **sentiment analysis** on text data, classifying each input as either **Positive** or **Negative** sentiment.  
It was built using two machine learning models — **Logistic Regression** and **Naive Bayes** — to compare performance and predictions.

---

## 🚀 Features

* Classifies text into **Positive** or **Negative** sentiment  
* Uses **two different models** for prediction: Logistic Regression & Naive Bayes  
* Includes **text preprocessing pipeline**: tokenization, stopword removal, lemmatization  
* Displays both models’ predictions for the same input text  

---

## 📊 Dataset

**Source**: IMDb Movie Reviews Dataset

* Pre-labeled text data  
* Binary sentiment labels:  
  * `1 = Positive`  
  * `0 = Negative`

---

## 🛠️ Preprocessing Steps

1. **Lowercasing** – All text converted to lowercase for consistency  
2. **Tokenization** – Splitting text into individual words  
3. **Stopword Removal** – Removing common English words that don’t carry sentiment  
4. **Lemmatization** – Reducing words to their base form (e.g., “running” → “run”)  
5. **Vectorization** – Using **TF-IDF** to transform text into numerical features

---

## 📊 Model Summary

* **Logistic Regression** – Linear model for binary classification  
* **Naive Bayes** – Probabilistic classifier, effective for text data  
* **Target** – Binary classification (Positive or Negative)  
* **Evaluation** – Accuracy score & prediction examples for both models

---

## 📌 About
Developed as part of an **NLP internship** to explore sentiment analysis using classical machine learning models and text preprocessing techniques.
