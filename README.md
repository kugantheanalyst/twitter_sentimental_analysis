# 🐦 Twitter Sentiment Analysis

## 📖 Project Overview
This project aims to classify tweets into **Positive, Neutral, or Negative** sentiments using **Deep Learning (LSTM)**. It includes data preprocessing, model training, and a **Streamlit web app** for real-time sentiment analysis.

## 🚀 Features
- **Data Cleaning**: Removing special characters, converting text to lowercase.
- **Tokenization & Padding**: Using `Tokenizer` and `pad_sequences`.
- **LSTM Model**: A neural network trained to classify tweets into sentiments.
- **Streamlit Web App**: A user-friendly interface to analyze tweet sentiment.

## 🛠️ Tech Stack
- **Programming Language**: Python
- **Deep Learning**: TensorFlow/Keras
- **NLP**: Tokenization, LSTM
- **Web App**: Streamlit
- **Libraries**: `pandas`, `numpy`, `tensorflow`, `sklearn`, `streamlit`

## 📦 Dataset
The dataset (`Twitter_Data.csv`) contains:
- `clean_text`: Preprocessed tweets.
- `sentiment`: Labels - Negative, Neutral, Positive.

## 🛠️ Installation
Ensure Python is installed, then install dependencies:

```bash
# Clone the repository
git clone https://github.com/kugantheanalyst/twitter-sentiment-analysis.git
cd twitter-sentiment-analysis

# Install required packages
pip install -r requirements.txt
