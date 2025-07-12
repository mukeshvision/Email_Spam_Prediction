# Spam Mail Prediction using Machine Learning

A machine learning-based project to classify emails as **spam** or **not spam (ham)** using natural language processing techniques and classification algorithms. This project uses a labeled dataset of email texts and applies a variety of preprocessing, vectorization, and classification steps to build a predictive model.

---

## Project Objective

The main goal of this project is to develop an intelligent spam filter that can accurately detect and classify email messages into spam or ham. It aims to:

- Clean and process raw email text data.
- Apply ML techniques and convert text into numerical form.
- Train a classification model to predict whether an email is spam or not.
- Evaluate and validate the model performance.

---

## Dataset

- **File**: `mail_data.csv`
- **Records**: 5572 email messages
- **Features**:
  - `Category`: Label indicating whether the email is "ham" or "spam".
  - `Message`: The raw content of the email.

The dataset is pre-labeled and ideal for supervised machine learning tasks.

---

## Technologies & Libraries Used

- Python 3
- NumPy
- Pandas
- Scikit-learn

---

## Methodology

### 1. Data Preprocessing
- Removed null entries and duplicates
- Converted text to lowercase
- Removed punctuation, stopwords, and performed tokenization
- Vectorized the text using **TF-IDF** (Term Frequency-Inverse Document Frequency)


### 2. Model Building
- Split dataset into train/test (80/20)
- Trained multiple classifier:
  - Logistic Regression
- Evaluated using accuracy

### 3. Model Evaluation
- Achieved accuracy: **96.7%**
