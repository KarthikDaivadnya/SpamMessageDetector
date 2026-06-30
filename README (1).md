# 📧 Spam Message Detector — NLP & Machine Learning

An end-to-end machine learning web app that classifies SMS/email text as **Spam** or **Ham** (legitimate) in real time, using NLP preprocessing and a Logistic Regression classifier achieving **97.77% accuracy**.

---

## 📌 Overview

This project implements a complete text classification pipeline — from raw text to a deployed web app — using classical NLP techniques and machine learning. Built on the UCI SMS Spam Collection dataset, it demonstrates the full lifecycle of an ML product: data cleaning, feature engineering, model selection, and evaluation.

---

## ✨ Features

- 🔍 Real-time spam/ham classification
- 📊 Spam probability confidence score
- 🧹 Full NLP preprocessing pipeline (tokenization, stopword removal, stemming)
- 🤖 Compares 11 ML models and auto-selects the best performer


---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| **Language** | Python |
| **Data Handling** | Pandas, NumPy |
| **NLP** | NLTK (Tokenization, Stopwords, Porter Stemmer) |
| **Feature Extraction** | TF-IDF (Scikit-learn) |
| **ML Models** | Logistic Regression, Multinomial Naive Bayes, SVC, KNeighborsClassifier, DecisionTreeClassifier, RandomForestClassifier, GradientBoostingClassifier,AdaBoostClassifier, ExtraTreesClassifier, BaggingClassifier, XGBClassifier |

| **Model Persistence** | Joblib |


---

## ⚙️ How It Works

```
Raw Text
   ↓
Lowercase + Remove Punctuation
   ↓
Tokenization
   ↓
Stopword Removal + Stemming
   ↓
TF-IDF Vectorization
   ↓
ML Model (Logistic Regression)
   ↓
Spam / Ham + Confidence %
```

---

## 🧠 Dataset

[UCI SMS Spam Collection Dataset](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection) — 5,574 labeled SMS messages (ham/spam), widely used as a benchmark for spam classification tasks.

---

## 🔮 Future Improvements

- [ ] Add spam probability heatmap for individual words
- [ ] Phishing-specific keyword detection
- [ ] Email history logging
- [ ] Multi-language support
- [ ] Deploy on Hugging Face Spaces

---

## 👤 Author

**Karthik M Daivadnya**
B.Tech Computer Science — Bapuji Institute of Engineering and Technology
[GitHub](https://github.com/KarthikDaivadnya) • [LinkedIn](https://www.linkedin.com/in/karthik-daivadnya)

---