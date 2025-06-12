# 📧 Email Spam Detection Using Machine Learning

This project aims to classify emails into *spam* or *ham* using various Natural Language Processing (NLP) and machine learning techniques. It focuses on preprocessing, feature engineering, and evaluating multiple classification models to optimize performance.

## 🧠 Key Features

- **Preprocessing Pipeline**: Tokenization, lowercasing, stopword removal, and symbol filtering using NLTK.
- **Feature Extraction**:
  - Bag-of-Words
  - TF-IDF
  - Bigrams, Trigrams
  - Sentiment scores
- **Classification Models**:
  - Gaussian Naive Bayes
  - Logistic Regression
  - Random Forest
  - (Unsuccessful) TensorFlow Bi-LSTM
- **Evaluation Metrics**: Precision, Recall, F1-Score, and Accuracy using 10-fold Cross Validation.

## 📊 Results Summary

| Model                | Accuracy | Best For                       |
|---------------------|----------|--------------------------------|
| Logistic Regression | **98%**  | Balanced performance & interpretability |
| Naive Bayes         | 94%      | Fast baseline model            |
| Random Forest       | 90%      | Strong but risk of overfitting |
| TensorFlow Bi-LSTM  | 49.75%   | Unsuccessful due to limited data |

## 📁 Project Structure

- `notebook/` – Jupyter Notebook with complete code and results
- `requirements.txt` – Python packages required to run the notebook
- `.gitignore` – Excludes cache, logs, and system-specific files

## 📚 Dataset

The dataset consists of plain-text email files stored in two folders:
- `spam/`: Contains emails labeled as spam.
- `ham/`: Contains emails labeled as legitimate (ham).

This dataset was provided for academic use and is not publicly available for redistribution.

## Acknowledgments

This project was developed as part of an academic study on Natural Language Processing and Machine Learning.
