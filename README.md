# Course Review Sentiment Analysis Using Machine Learning

## Project Overview
This project focuses on analyzing and classifying online course reviews into **positive** and **negative** sentiments using **Natural Language Processing (NLP)** and **Machine Learning** techniques. The goal is to compare multiple traditional ML models and evaluate their performance on real-world textual data.

The dataset consists of thousands of course reviews, which are cleaned, vectorized, and classified using different algorithms.

---

## Dataset Description
- Data source: JSON file containing course reviews
- Total courses: 8,479
- Total reviews after preprocessing: 14,616
- Labels:
  - `liked course` → **1**
  - `disliked course` → **0**

---

## Technologies Used
- **Python**
- **Pandas & NumPy** – data handling
- **NLTK** – text preprocessing & stopword removal
- **Scikit-learn** – feature extraction & modeling
- **Transformers (BERT Tokenizer)** – tokenization exploration
- **Matplotlib & Seaborn** – visualization

---

## Methodology

### 1. Data Loading & Preparation
- Loaded course review data from a JSON file
- Flattened nested review structures
- Removed missing values
- Mapped text labels to numerical values

---

### 2. Text Preprocessing
- Lowercasing text
- Removing punctuation and non-alphabet characters
- Removing English stopwords
- Calculating review length statistics

---

### 3. Feature Extraction
- Used **TF-IDF Vectorization** with a maximum of 5000 features
- Converted textual reviews into numerical vectors

---

### 4. Model Training
Three different machine learning models were trained and compared:

- **Logistic Regression**
- **Multinomial Naive Bayes**
- **Random Forest Classifier**

Data was split into training and testing sets using **stratified sampling**.

---

### 5. Evaluation Metrics
Each model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix visualization

---

## Results
The project demonstrates how traditional machine learning models perform on text classification tasks. Logistic Regression and Naive Bayes showed strong performance for sentiment classification, while Random Forest provided a useful comparison for ensemble-based methods.

---

## Key Learnings
- Practical NLP preprocessing techniques
- Importance of text cleaning in ML performance
- Comparison between different classification algorithms
- Evaluation of sentiment analysis models using multiple metrics


