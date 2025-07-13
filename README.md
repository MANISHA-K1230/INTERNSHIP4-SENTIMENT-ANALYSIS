# INTERNSHIP4-SENTIMENT-ANALYSIS

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: MANISHA K

*INTERN ID*: CT04DG1611

*DOMAIN*: DATA ANALYTICS

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTHOSH KUMAR

*PROJECT DISCRIPTION*:

# Sentiment Analysis using NLP Techniques

This project performs **sentiment analysis** on textual data (like tweets or reviews) using Natural Language Processing (NLP). The goal is to classify the sentiments into **positive**, **negative**, or **neutral** categories.

## 🚀 Features

- Text preprocessing (lowercasing, removing stopwords, etc.)
- Tokenization and vectorization (TF-IDF)
- Model training using Logistic Regression
- Evaluation metrics (accuracy, classification report)
- Prediction on new text data

## 📁 Project Structure

Sentiment-Analysis-NLP/
├── data/
├── notebooks/
├── src/
├── requirements.txt
└── README.md


## 🧪 Dataset

The dataset used is `sample_reviews.csv` which contains:
- `text`: The review or tweet text
- `label`: The sentiment (positive/negative/neutral)

## 🛠️ Installation

git clone : https://github.com/MANISHA-K1230/INTERNSHIP4-SENTIMENT-ANALYSIS
cd Sentiment-Analysis-NLP
pip install -r requirements.txt

## 🧠 How it Works

1. Load and clean the dataset.
2. Preprocess text data using `nltk`.
3. Convert text to numerical vectors using `TfidfVectorizer`.
4. Train a **Logistic Regression** classifier.
5. Evaluate and predict sentiments.

## 📊 Sample Output

Accuracy: 0.89
Classification Report:
              precision    recall  f1-score   support
    positive       0.90      0.88      0.89       200
    negative       0.88      0.89      0.88       200
     neutral       0.89      0.91      0.90       200

## 📦 Dependencies

- pandas
- scikit-learn
- nltk
- matplotlib

Install via:

pip install -r requirements.txt

##👩‍💻 Author

Manisha K-Sentiment Analysis internship project (codtech)
