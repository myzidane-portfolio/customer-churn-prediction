# 📊 Customer Churn Prediction Project

## 📌 Project Overview

Customer churn is a critical business problem where companies aim to identify customers who are likely to stop using their services.
This project focuses on building an **end-to-end machine learning pipeline** to analyze customer behavior and predict churn using structured customer data.

The project demonstrates practical skills in:

* Data cleaning
* Exploratory data analysis (EDA)
* Machine learning modeling
* Model improvement and evaluation

---

## 🎯 Project Objectives

* Understand customer behavior through data exploration
* Identify key factors influencing customer churn
* Build and evaluate predictive models for churn classification
* Provide insights that support business decision-making

---

## 🗂 Project Structure

```
customer-churn-project/
│
├── data/
│   ├── raw_data.csv          # Original dataset
│   └── cleaned_data.csv      # Cleaned dataset
│
├── notebooks/
│   ├── data_cleaning.ipynb
│   ├── eda.ipynb
│   ├── churn_modeling.ipynb
│   └── churn_model_improvement.ipynb
│
├── requirements.txt
└── README.md
```

---

## 🧹 Data Cleaning

**Notebook:** `data_cleaning.ipynb`

Key steps:

* Dataset validation and inspection
* Missing value analysis (no missing values found)
* Duplicate checks
* Target variable validation
* Export of a clean and modeling-ready dataset

✔ Result: A consistent and clean dataset ready for analysis and modeling.

---

## 🔍 Exploratory Data Analysis (EDA)

**Notebook:** `eda.ipynb`

Key insights:

* Customers with shorter tenure are more likely to churn
* Usage-based features strongly correlate with churn behavior
* Certain customer categories show higher churn rates
* Feature correlations highlight potential multicollinearity

Visualizations include:

* Churn distribution
* Feature distributions
* Churn vs feature comparisons
* Correlation heatmap

---

## 🤖 Modeling

**Notebook:** `churn_modeling.ipynb`

Steps:

* Feature–target separation
* Train-test split with stratification
* Feature scaling
* Baseline Logistic Regression model
* Model evaluation using accuracy, confusion matrix, and classification report

✔ Purpose: Establish a strong and interpretable baseline model.

---

## 🚀 Model Improvement

**Notebook:** `churn_model_improvement.ipynb`

Enhancements:

* Regularized Logistic Regression
* Random Forest Classifier
* Model comparison using Accuracy and ROC-AUC
* Feature importance analysis

✔ Result: Improved performance and better understanding of churn drivers.

---

## 📈 Technologies & Tools

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn
* Jupyter Notebook

---

## ⚙️ Installation & Usage

Clone the repository and install dependencies:

```bash
pip install -r requirements.txt
```

Run notebooks in the following order:

1. `data_cleaning.ipynb`
2. `eda.ipynb`
3. `churn_modeling.ipynb`
4. `churn_model_improvement.ipynb`

---

## 🧠 Key Takeaways

* Customer tenure and usage behavior are strong churn indicators
* Machine learning models can effectively support churn prediction
* Feature importance provides actionable business insights

---

## 📌 Future Improvements

* Hyperparameter tuning with GridSearchCV
* Gradient Boosting or XGBoost models
* Cost-sensitive learning for churn imbalance
* Model deployment (API or dashboard)

---

## 👤 Author

**Mohamad Yasid Zidane**
Aspiring Data Scientist
📧 [your.email@example.com](mohamadyasidzidane@gmail.com)

---

⭐ *If you find this project useful, feel free to star the repository!*
