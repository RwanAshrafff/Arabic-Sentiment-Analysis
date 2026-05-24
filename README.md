# 🧠 Arabic Sentiment Analysis

An Arabic Natural Language Processing (NLP) project focused on sentiment analysis using Machine Learning and Word Embedding techniques. This project applies preprocessing, feature extraction, and classification methods to analyze Arabic text and classify sentiments into positive and negative categories.

---

## 🚀 Project Overview

This project explores different NLP techniques for processing Arabic text and building sentiment analysis models using both traditional machine learning and word embedding approaches.

The project includes:
- Arabic text preprocessing
- Text cleaning & normalization
- Tokenization
- Feature extraction
- Word embeddings using AraVec & FastText
- Sentiment classification and evaluation

---

## 🛠️ Technologies & Libraries

- Python
- Pandas
- NumPy
- NLTK
- Gensim
- Scikit-learn
- TensorFlow / Keras

---

## 📌 NLP Techniques Used

### 🔹 Text Preprocessing
- Removing punctuation
- Removing URLs & mentions
- Arabic normalization
- Tokenization
- Stopword removal

### 🔹 Feature Extraction
- Bag of Words (BoW)
- TF-IDF
- N-grams

### 🔹 Word Embeddings
- AraVec
- FastText
  
### 🔹 Models
- Logistic Regression
- Arabert
- Marbert
- Camelbert
- Qarib

---

## 📊 Dataset

The dataset contains Arabic text samples labeled with sentiment classes:

| Label | Text |
|------|------|
| Positive | ممتاز نوعا ما |
| Negative | الخدمة سيئة جدا |

---

## 📈 Evaluation Metrics

The models are evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## ⚡ Example Workflow

```python
# Tokenization
tokens = text.split()

# Generate word embedding
vector = model.wv["ممتاز"]

# Predict sentiment
prediction = model.predict(X_test)
```
If you found this project useful, feel free to ⭐ the repository!
