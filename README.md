# sms-spam-classifier
A web-based SMS spam classifier built using Streamlit, scikit-learn, and Natural Language Processing (NLP) techniques. The app allows users to input a text message and predicts whether it is spam or not.
## 🚀 Features
- Preprocessing using NLTK (stopwords, stemming, tokenization)
- TF-IDF vectorization for feature extraction
- Multinomial Naive Bayes classifier
- Streamlit web interface for real-time classification
- Trained on a real-world SMS Spam dataset

## 🛠️ Tech Stack
- Python
- Scikit-learn
- NLTK
- Pandas
- Streamlit

## 🧠 How It Works
1. User inputs a message.
2. The message is cleaned and transformed using NLP techniques.
3. It is then converted into a numerical vector using TF-IDF.
4. The trained model predicts whether it is spam or not.

## 📄 Dataset

This project uses the [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset) from UCI and Kaggle.

To use it:
1. Download the dataset from the link above.
2. Place `SMSSpamCollection` in the project’s `data/` directory (create one if it doesn't exist).

## Project Structure

email-classification/
├── data/
│   ├── train.csv       # Training dataset
│   ├── test.csv        # Testing dataset
├── src/
│   ├── preprocess.py   # Email preprocessing scripts
│   ├── model.py        # Model training and evaluation scripts
│   ├── predict.py      # Email classification prediction scripts
├── notebooks/
│   ├── EDA.ipynb       # Exploratory Data Analysis notebook
│   ├── ModelTraining.ipynb  # Model training notebook
├── requirements.txt    # Required Python libraries
├── README.md           # Project readme file


