# 🛒 Flipkart Customer Support CSAT Prediction using Machine Learning

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/XGBoost-Model-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Google%20Colab-Notebook-yellow?style=for-the-badge&logo=googlecolab">
</p>

---

# 📌 Project Overview

Customer Satisfaction (CSAT) is one of the most important business metrics for measuring customer experience.

This project focuses on analyzing Flipkart Customer Support data and building Machine Learning models to predict customer satisfaction based on support interactions, issue details, product information, handling time, and customer feedback.

The project follows a complete Data Science workflow including Data Cleaning, EDA, Feature Engineering, Statistical Testing, Data Preprocessing, Machine Learning, and Model Evaluation.

---

# 🎯 Project Objective

The primary objectives of this project are:

✅ Analyze customer support interactions

✅ Identify factors affecting customer satisfaction

✅ Generate business insights through EDA

✅ Build predictive Machine Learning models

✅ Compare multiple algorithms and select the best model

✅ Help businesses improve customer support quality

---

# 📊 Dataset Information

The dataset contains customer support records with information such as:

* 📞 Channel Name
* 📂 Issue Category
* 📋 Sub-Category
* 💬 Customer Remarks
* 🏙️ Customer City
* 📦 Product Category
* 💰 Item Price
* ⏳ Connected Handling Time
* 👨‍💼 Agent Details
* 🌙 Agent Shift
* 📈 Tenure Bucket
* ⭐ CSAT Score (Target Variable)

**Dataset Size:** 85,000+ Customer Support Records

---

# 🚀 Project Workflow

## 1️⃣ Data Understanding

* Dataset Overview
* Shape Analysis
* Data Type Inspection
* Missing Value Analysis
* Duplicate Value Detection

---

## 2️⃣ Exploratory Data Analysis (EDA)

📊 CSAT Score Distribution

📊 Product Category Analysis

📊 Customer Support Channel Analysis

📊 Agent Shift Analysis

📊 Handling Time Analysis

📊 Correlation Analysis

📊 Customer Remark Analysis

---

## 3️⃣ Data Wrangling

* Datetime Conversion
* Data Cleaning
* Data Standardization
* Data Validation

---

## 4️⃣ Statistical Hypothesis Testing

To validate assumptions statistically:

✅ Chi-Square Test

✅ Mann-Whitney U Test

✅ Significance Testing using p-values

---

## 5️⃣ Feature Engineering

Created meaningful features including:

* ⏱️ Response Time Calculation
* 📅 Time-based Features
* 📈 Derived Business Features

These engineered features improved model performance significantly.

---

## 6️⃣ Text Data Preprocessing

Customer remarks were cleaned and transformed using:

* Expand Contractions
* Lower Casing
* Remove Punctuation
* Remove URLs
* Remove Digits
* Remove Stopwords
* Tokenization
* Text Normalization
* POS Tagging
* Text Vectorization

---

## 7️⃣ Data Preprocessing

### 🔹 Missing Value Treatment

Handled null values using suitable imputation methods.

### 🔹 Outlier Treatment

Applied IQR-based Winsorization to reduce the effect of extreme values.

### 🔹 Categorical Encoding

Converted categorical variables into numerical representations.

### 🔹 Feature Selection

Selected important features for efficient model training.

### 🔹 Data Transformation

Prepared data in a model-friendly format.

### 🔹 Data Scaling

Standardized numerical variables using StandardScaler.

---

## 8️⃣ Handling Imbalanced Dataset

Implemented:

### 🔥 SMOTE (Synthetic Minority Oversampling Technique)

This technique generated synthetic samples for minority classes and improved model learning.

---

# 🤖 Machine Learning Models

The following models were implemented and evaluated:

## 📌 Logistic Regression

Baseline classification model used for initial performance benchmarking.

## 🌲 Random Forest Classifier

Ensemble learning technique using multiple decision trees.

## ⚡ XGBoost Classifier

Advanced gradient boosting algorithm known for high predictive performance.

---

# 🎯 Hyperparameter Tuning

To improve model performance:

✅ RandomizedSearchCV

✅ Stratified Cross Validation

✅ Parameter Optimization

This helped identify the best-performing model configuration.

---

# 📈 Model Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* ROC-AUC Score
* Confusion Matrix

---

# 🔍 Feature Importance Analysis

Feature importance analysis was performed to identify factors that most strongly influence customer satisfaction.

Key influential features included:

* ⏱️ Response Time
* 📦 Product Category
* 📂 Issue Category
* 📞 Support Channel
* 👨‍💼 Agent Information
* ⌛ Handling Time

---

# 🛠️ Tech Stack

### Programming Language

🐍 Python

### Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* NLTK
* SciPy
* Imbalanced-Learn

### Development Environment

💻 Google Colab

📓 Jupyter Notebook

---

# 📂 Project Structure

```text
📁 Flipkart-CSAT-Prediction
│
├── 📓 Flipkart_CSAT_Prediction.ipynb
├── 📊 Customer_support_data.csv
├── 📄 README.md
└── 📋 requirements.txt
```

---

# 💼 Business Impact

This solution can help organizations:

✅ Improve Customer Satisfaction

✅ Reduce Resolution Time

✅ Improve Agent Performance

✅ Identify Customer Pain Points

✅ Make Data-Driven Decisions

✅ Enhance Overall Customer Experience

---

# 🔮 Future Enhancements

* Deep Learning Models
* Sentiment Analysis
* Real-Time Prediction System
* Interactive Dashboard
* Web Deployment using Flask/FastAPI

---

# 👨‍💻 Author

## Vamsee

🎓 B.Tech Computer Science Engineering

📊 Data Science Enthusiast

🤖 Machine Learning Practitioner

💡 Passionate about solving real-world problems using AI & Data

---

# ⭐ Conclusion

This project demonstrates a complete end-to-end Data Science workflow, starting from raw customer support data and ending with a highly optimized Machine Learning model.

By combining EDA, Statistical Analysis, Feature Engineering, Data Preprocessing, and Machine Learning, the project successfully predicts customer satisfaction and provides valuable business insights for improving customer support services.

⭐ If you found this project useful, consider giving it a star!
