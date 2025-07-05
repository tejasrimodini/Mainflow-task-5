
# 📊 Data Analysis and Data Science with Python - Classification Tasks

This repository contains solutions for **Task 1** and **Task 2** from the project:  
**"Data Analysis and Data Science with Python - 5"**

---

## 🔍 Project Overview

The project focuses on two classification problems using Python and standard machine learning libraries.

### ✅ Task 1: Student Pass/Fail Prediction

**Objective:**  
Predict whether a student will pass or fail based on their **Study Hours** and **Attendance**.

#### 📁 Dataset:
- Columns:
  - `Study Hours`: Number of hours a student studies per week
  - `Attendance`: Percentage of classes attended
  - `Pass`: 1 = Pass, 0 = Fail (target)

#### 🔧 Key Steps:
- Check and handle missing values
- Visualize Study Hours vs Attendance
- Train a **Logistic Regression** model
- Evaluate using **accuracy** and **confusion matrix**

#### 📈 Deliverables:
- Cleaned dataset with imputed missing values
- Trained model
- Accuracy score and confusion matrix plot

---

### ✅ Task 2: Sentiment Analysis using NLP

**Objective:**  
Classify customer reviews as **positive** or **negative** using Natural Language Processing.

#### 📁 Dataset:
- `Review Text`: Customer review (text)
- `Sentiment`: `positive` or `negative`

#### 🧹 Preprocessing:
- Convert to lowercase
- Remove punctuation and stopwords (using NLTK)
- Vectorize text using **TF-IDF**

#### 🧠 Model:
- Train a **Logistic Regression** classifier
- Evaluate using:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - Confusion matrix

#### 📊 Insights:
- Print examples of correctly/incorrectly predicted reviews
- Display evaluation metrics for the model

---

## 🛠️ Tools and Libraries

- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`
- `nltk`

