# 📈 Stock Market Sentiment Analysis 

This project performs sentiment analysis on stock-related textual data using various machine learning and deep learning models to classify the sentiment (e.g., positive, negative, or neutral). The goal is to understand how different models perform on textual stock data and identify the most accurate approach.

---

## 🔧 Technologies Used

- **Python**
- **Google Colab**
- **Pandas & NumPy** – Data handling
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – ML models (Naive Bayes, Logistic Regression)
- **TensorFlow (Keras)** – Deep Learning (LSTM)
- **NLTK** – Text preprocessing (stopwords, stemming)

---

## 📁 Dataset

- The dataset `Stock data.csv` consists of:
  - `Text`: Stock-related headlines/news
  - `Sentiment`: Labels (positive, negative, neutral)

---

## 🧹 Preprocessing Steps

1. Lowercasing all text
2. Removing non-alphabetical characters
3. Removing stopwords using NLTK
4. Applying stemming (Porter Stemmer)

---

## 🤖 Models Used

| Model                | Features Used       | Notes                              |
|---------------------|---------------------|------------------------------------|
| Naive Bayes          | Bag of Words         | Simple and fast probabilistic model |
| Logistic Regression  | Bag of Words         | Performs better than Naive Bayes   |
| LSTM (Deep Learning) | Word Embeddings      | Captures sequential text patterns  |

---

## 📊 Results

| Model               | Accuracy |
|--------------------|----------|
| Naive Bayes         | 71.44%   |
| Logistic Regression | 75.98%   |
| LSTM                | 71.34%   |

---

## ✅ Conclusion

- **Logistic Regression** performed the best among the three models with **~76% accuracy**.

