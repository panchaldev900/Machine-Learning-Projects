# 🛍️ Black Friday Sales Prediction

## 📌 Project Overview

The Black Friday Sales Prediction project aims to predict the purchase amount of customers during Black Friday sales events using Machine Learning techniques. By analyzing customer demographics and product-related information, the model estimates how much a customer is likely to spend.

This project demonstrates the complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and model evaluation.

---

## 🎯 Objective

To build a regression model that predicts customer purchase amounts based on:

- Gender
- Age
- Occupation
- City Category
- Years in Current City
- Marital Status
- Product Categories

---

## 📂 Dataset Features

| Feature | Description |
|----------|-------------|
| User_ID | Unique customer ID |
| Product_ID | Unique product ID |
| Gender | Customer gender |
| Age | Customer age group |
| Occupation | Occupation code |
| City_Category | Category of city |
| Stay_In_Current_City_Years | Years customer stayed in city |
| Marital_Status | Marital status |
| Product_Category_1 | Primary product category |
| Product_Category_2 | Secondary product category |
| Product_Category_3 | Tertiary product category |
| Purchase | Purchase amount (Target Variable) |

---

## 🔍 Exploratory Data Analysis (EDA)

The following analyses were performed:

- Purchase Distribution Analysis
- Gender vs Purchase Analysis
- Age vs Purchase Analysis
- Occupation vs Purchase Analysis
- City Category vs Purchase Analysis
- Correlation Heatmap

### Key Insights

- Customer demographics influence purchasing behavior.
- Certain age groups contribute more to total sales.
- Purchase patterns vary across city categories.
- Occupation has a noticeable impact on spending habits.

---

## ⚙️ Data Preprocessing

- Handled missing values in Product_Category_2 and Product_Category_3.
- Removed unnecessary columns such as User_ID and Product_ID.
- Converted categorical variables into numerical format.
- Prepared data for machine learning models.

---

## 🤖 Machine Learning Models Used

### 1. Linear Regression
Used as a baseline regression model.

### 2. Random Forest Regressor
Used to capture non-linear relationships and improve prediction accuracy.

### 3. XGBoost Regressor
Used as an advanced boosting algorithm for optimized performance.

---

## 📊 Model Evaluation Metrics

The models were evaluated using:

- MAE (Mean Absolute Error)
- RMSE (Root Mean Squared Error)
- R² Score

### Best Model Performance (XGBoost)

| Metric | Value |
|----------|----------|
| MAE | 2193.10 |
| RMSE | 2923.11 |
| R² Score | 0.6599 |

---

## 🏆 Model Comparison

| Model | R² Score |
|----------|----------|
| Linear Regression | 0.1514 |
| Random Forest | 0.6273 |
| XGBoost | 0.6599 |

XGBoost achieved the highest R² score and was selected as the final model.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- XGBoost
- Jupyter Notebook

---

## 📈 Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Train-Test Split
6. Model Training
7. Model Evaluation
8. Model Comparison
9. Performance Analysis
10. Final Prediction

---

## 💡 Business Impact

This model can help retailers:

- Understand customer spending behavior.
- Improve inventory planning.
- Optimize marketing campaigns.
- Make data-driven business decisions during sales events.

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV.
- Deployment using Streamlit.
- Real-time prediction interface.
- Advanced feature engineering techniques.

---

## 👨‍💻 Author

Dev Panchal

Machine Learning Enthusiast | AI & Data Science Learner