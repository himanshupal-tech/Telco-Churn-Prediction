# 📊 Telco Customer Churn Prediction

## 📌 Project Overview

Customer churn is one of the biggest challenges for telecom companies. In this project, I performed Exploratory Data Analysis (EDA) to predict whether a customer is likely to churn based on customer demographics, account information, and subscribed services.

---

## 🎯 Objective

The objective of this project is to:

- Analyze customer behavior using EDA.
- Identify the factors that influence customer churn.
- Build a classification model to predict customer churn.

---

## 📂 Dataset

**Dataset:** IBM Telco Customer Churn Dataset

The dataset contains customer information such as:

- Gender
- Senior Citizen
- Partner
- Dependents
- Tenure
- Phone Service
- Internet Service
- Contract Type
- Payment Method
- Monthly Charges
- Total Charges
- Churn (Target Variable)

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📈 Exploratory Data Analysis (EDA)

The following visualizations were performed:

- Customer Churn Distribution
- Gender vs Churn
- Internet Service vs Churn
- Tenure Distribution
- Monthly Charges Distribution
- Boxplots for Numerical Features
- Scatter Plots
- Correlation Heatmap

### Key Insights

- Most customers did not churn.
- Gender has very little impact on churn.
- Customers with lower tenure are more likely to churn.
- Customers with Fiber Optic internet service have higher churn.
- Higher Monthly Charges are associated with higher churn.
- Total Charges strongly correlate with Tenure.

---

## 📁 Project Structure

'''
Telco-Churn-Prediction/
│
├── data/
│   └── Telco-Customer-Churn.csv
│
├── notebook/
│   └── telco_churn.ipynb
│
├── graphs/
│   ├── churn_countplot.png
│   ├── gender_churn.png
│   ├── tenure_histogram.png
│   ├── monthlycharges_histogram.png
│   ├── tenure_boxplot.png
│   ├── monthlycharges_boxplot.png
│   ├── internetservice_churn.png
│   ├── heatmap.png
│   ├── tenure_totalcharges_scatter.png
│   └── monthly_totalcharges_scatter.png
│
├── README.md
├── requirements.txt
└── .gitignore'''


📚 Skills Demonstrated

- Exploratory Data Analysis
- Data Visualization
- Python Programming

---


---

## ⭐ If you found this project useful, consider giving it a star!
