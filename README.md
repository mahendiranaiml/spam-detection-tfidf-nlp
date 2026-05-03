# 📧 Email Classification using NLP (Naive Bayes)

## 🚀 Overview

This project focuses on building an **Email Classification system** using Natural Language Processing (NLP).
The goal is to classify emails as **Spam (1)** or **Ham (0)**.

---

## 🧠 What I Learned

### 🔹 1. Text Preprocessing

* Cleaning raw email text
* Removing:

  * URLs
  * Email addresses
  * Special characters
* Handling:

  * Lowercasing
  * Extra spaces
* Understanding how **dirty data affects model performance**

---

### 🔹 2. TF-IDF (Text Vectorization)

* Converted text into numerical features using **TF-IDF**
* Learned:

  * Importance of word frequency
  * Difference between common vs important words
* Used:

  * `max_features`
  * `ngram_range`

---

### 🔹 3. N-grams

* Used **unigrams and bigrams**
* Helped capture:

  * Context (e.g., "free offer" vs "free")
* Improved model understanding of text patterns

---

### 🔹 4. Naive Bayes Model

* Implemented **Multinomial Naive Bayes**
* Learned:

  * Works well for text classification
  * Based on probability of words
* Understood:

  * Why it is a strong **baseline model**

---

### 🔹 5. Model Evaluation

* Evaluated using:

  * Precision
  * Recall
  * F1-score
* Learned:

  * **Precision vs Recall trade-off**
  * Importance of tuning for business needs

---

## ⚙️ Tech Stack

* Python 🐍
* Pandas
* Scikit-learn
* Regex (re)

---

## 📊 Workflow

1. Load dataset
2. Clean and preprocess text
3. Convert text → TF-IDF features
4. Train Naive Bayes model
5. Evaluate performance

---

## 📈 Key Insight

> In spam detection, **recall is often more important than precision**
> because missing spam is worse than false alarms.

---

## 📌 Future Improvements

* Try Logistic Regression
* Use advanced embeddings (Word2Vec, BERT)
* Improve feature engineering
* Handle class imbalance

---

## 💡 Conclusion

This project helped me understand the **end-to-end NLP pipeline** from raw text to model evaluation, along with real-world challenges like messy data and trade-offs in model performance.

---
