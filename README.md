# 📧 Email Auto Responder using NLP & Machine Learning

An intelligent email auto-responder that classifies customer support emails and generates appropriate replies using Natural Language Processing (NLP) and Machine Learning.

---

## 🚀 Overview

This project automates email replies by predicting the best-fit response class using supervised and deep learning models.

---

## 🛠️ Features

- Text preprocessing (tokenization, normalization, polite suffix removal)
- Trained multiple models:
  - SVM with TF-IDF
  - Logistic Regression
  - RNN
  - LSTM (Bidirectional)
  - GRU
- Performance comparison across models with F1-score and accuracy

---

## 📊 Results

| Model               | Accuracy | Macro F1 | Weighted F1 |
|--------------------|----------|----------|--------------|
| SVM                | 95.14%   | 0.49     | 0.93         |
| Logistic Regression| 94.72%   | 0.46     | 0.91         |
| RNN                | 95.14%   | 0.98     | 0.98         |
| LSTM               | 95.14%   | 0.49     | 0.93         |
| GRU                | 95.14%   | 0.50     | 0.94         |

> ✅ RNN achieved the most balanced performance across all classes.

## 🧠 Tech Stack

- Python, scikit-learn, TensorFlow/Keras  
- Pandas, NumPy  
- TF-IDF, Embedding layers  
- LabelEncoder

---
## 📌 Dataset

Used a labeled dataset of customer support emails and matching response classes. Replies were encoded as classification labels.
---

## 🔮 Future Work
- Connect to Gmail API or email service
- Real-time predictions via FastAPI
- Add multi-lingual support


