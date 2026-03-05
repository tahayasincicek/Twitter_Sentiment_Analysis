# Twitter Sentiment Analysis

This project performs **sentiment analysis on Twitter data using PySpark**.  
The goal is to classify tweets as **positive or negative** using machine learning models and different text feature extraction techniques.

---

## Overview

Social media platforms generate large amounts of unstructured text data.  
This project analyzes Twitter messages and builds machine learning models to determine the sentiment of each tweet.

Main steps of the project:

- Data loading with PySpark
- Text preprocessing
- Feature extraction
- Model training
- Model evaluation

---

## Technologies

- Python
- PySpark
- Apache Spark
- Machine Learning
- Natural Language Processing (NLP)
- Jupyter Notebook
- Scikit-learn
- Matplotlib

---

## Dataset

The dataset contains labeled Twitter messages.

Labels:

- **Positive**
- **Negative**

Each record contains:

- Tweet text
- Sentiment label

Since tweets are **unstructured text**, preprocessing and feature engineering are required before model training.

---

## Feature Engineering

Different feature extraction techniques are tested:

- **HashingTF + IDF**
- **CountVectorizer + IDF**
- **N-Grams**
- **Chi-Square feature selection**

These methods convert text data into numerical vectors that can be used by machine learning algorithms.

---

## Machine Learning Models

The following models are trained and compared:

- Logistic Regression
- Linear Support Vector Machine (Linear SVC)
- Naive Bayes

---

## Evaluation

Models are evaluated using:

- Accuracy
- Confusion Matrix

These metrics help compare the performance of different models and feature extraction methods.

---

## Project Structure

```
Twitter-Sentiment-Analysis
│
├── Twitter_Sentiment_Analysis.ipynb
└── README.md
```

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/yourusername/twitter-sentiment-analysis.git
```

Install dependencies:

```bash
pip install pyspark numpy matplotlib scikit-learn
```

Run the notebook:

```bash
jupyter notebook
```

Open:

```
Twitter_Sentiment_Analysis.ipynb
```

---

## Author

Taha Yasin Çiçek  
Software Engineering Student
