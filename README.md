# 📚 Sentiment & Genre Classification Using Deep Learning on Amazon Kindle Reviews

This final-year university project, developed by **Losheni Meenakshi Sundaram**, focuses on building robust sentiment and genre classifiers for Amazon Kindle book reviews. It uses a combination of **Multi-Layer Neural Network (MLNN)**, **LSTM**, and **Transformer-based hybrid models**, with advanced preprocessing, class balancing, and NLP techniques.

---

## 📌 Project Overview

The system classifies user reviews into:
- **Sentiment**: Positive, Neutral, or Negative
- **Genre**: One of the Top 50 book genres

The project integrates:
- **TF-IDF vectorization** and **padded tokenized sequences**
- **SMOTE** for class imbalance handling
- **RandomSearch Hyperparameter Tuning**
- **Hybrid Models**: MLNN + LSTM, Transformer + MLNN

It aims to improve book recommendation systems, automate review analysis, and enhance content tagging.

---

## 🧠 Models Implemented

- **Baseline Models**: Logistic Regression, Naive Bayes, Random Forest
- **Advanced DL Models**: MLNN, LSTM, FNN
- **Hybrid Architectures**:
  - MLNN + LSTM (parallel branches)
  - Transformer + MLNN (attention + statistical features)

---

## 🧰 Technologies Used

- Python 3.10
- TensorFlow / Keras
- KerasTuner (Random Search)
- Scikit-learn, Pandas, NumPy
- Matplotlib, Seaborn (for evaluation)

---

## 📦 Dataset

- **Source**: https://www.kaggle.com/datasets/mohamedbakhet/amazon-books-reviews
- **Fields Used**:
  - `Title`, `review/text`, `review/score`, `categories`, `authors`
- **Targets**:
  - `Sentiment`: Mapped from review scores (1–5 stars)
  - `Genre`: Multi-label, limited to top 50 most frequent genres

---

## 🚀 How to Run This Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/kindle_sentiment_genre_classification.git
   cd kindle_sentiment_genre_classification
