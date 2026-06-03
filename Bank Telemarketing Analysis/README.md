# Bank Marketing Analysis & Customer Subscription Prediction

## 📌 Project Overview

This project analyzes a bank marketing campaign dataset and builds machine learning models to predict whether a customer will subscribe to a term deposit.

The project includes:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Data Preprocessing
* Machine Learning Model Building
* Model Evaluation
* Business Insights & Recommendations

The objective is to identify key factors that influence customer subscription decisions and help improve future marketing campaigns.

---

## 📊 Dataset Information

The dataset contains customer demographic information, financial details, and marketing campaign interactions.

### Features Include:

* Age
* Job
* Marital Status
* Education
* Balance
* Housing Loan
* Personal Loan
* Contact Type
* Campaign Information
* Previous Campaign Outcome
* Month of Contact

### Target Variable

* **Response**

  * Yes → Customer subscribed to term deposit
  * No → Customer did not subscribe

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 🔍 Data Preprocessing

The following preprocessing steps were performed:

* Missing Value Handling
* Duplicate Check
* Outlier Treatment
* Feature Engineering
* Encoding Categorical Variables
* Feature Scaling
* Train-Test Split

---

## 📈 Exploratory Data Analysis (EDA)

EDA was performed to understand customer behavior and campaign performance.

### Key Analyses

* Age Group Analysis
* Balance Group Analysis
* Monthly Campaign Analysis
* Previous Campaign Outcome Analysis
* Correlation Analysis

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

### 1. Logistic Regression

Used as a baseline classification model.

### 2. Random Forest Classifier

Used to improve prediction performance and analyze feature importance.

---

## 📊 Model Performance

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | 89.57%   |
| Random Forest       | 89.57%   |

> Note: Initial 100% accuracy was identified as data leakage caused by the target-related feature (`response_yes`). After removing leakage features, realistic and reliable model performance was achieved.

---

## 📉 Visualizations

### Correlation Heatmap

Displays relationships among numerical features.

### Confusion Matrix

Evaluates model prediction performance.

### Feature Importance

Shows the most influential features affecting customer subscription decisions.

---

## 💡 Business Insights

* Customers with higher account balances are more likely to subscribe.
* Previous successful campaign outcomes significantly increase subscription probability.
* Age influences customer response behavior.
* Marketing campaign timing impacts conversion rates.
* Targeted campaigns can improve marketing efficiency and reduce operational costs.

---

## 🚀 Future Improvements

* Hyperparameter Tuning
* XGBoost Implementation
* Cross Validation
* Model Deployment using Streamlit
* Real-Time Prediction System
* Interactive Dashboard

---

## 📂 Project Structure

```text
Bank-Marketing-Analysis/
│
├── Bank_Marketing_Analysis.ipynb
├── README.md
├── images/
│   ├── confusion_matrix.png
│   ├── feature_importance.png
│   └── correlation_heatmap.png
```

---

## 📬 Author

**Dev Panchal**

GitHub: https://github.com/panchaldev900

---

## ⭐ Project Highlights

* End-to-End Machine Learning Workflow
* Comprehensive Exploratory Data Analysis
* Business-Oriented Insights
* Classification Modeling
* Feature Importance Analysis
* Realistic Model Evaluation
