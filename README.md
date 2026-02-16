# Predictive-HR-Analytics-Employee-Performance-Modeling
Built an end-to-end machine learning model to predict employee performance ratings using HR data. Conducted EDA, feature engineering, and implemented Logistic Regression, Decision Tree, and Random Forest models. Evaluated performance using accuracy, identifying key factors influencing employee performance.

## 🔷 Project Overview

This project focuses on analyzing employee performance data and building predictive machine learning models to classify employee performance ratings.

The objective is to help HR and management teams identify key drivers of performance and support data-driven workforce decisions such as promotions, training, and retention planning.

This is a supervised classification problem where the target variable is Performance Rating.

## 🔷 Business Problem

INX Future Inc aims to improve employee performance evaluation by leveraging data insights. Traditional evaluation methods may introduce bias and lack predictive capability.

This project addresses:

What factors influence employee performance?

Can we predict performance ratings using historical data?

Which machine learning model performs best for this classification task?

## 🔷 Dataset Information

Dataset: INX_Future_Inc_Employee_Performance_CDS_Project2_Data_V1.8.xls

Records: ~1200 employees

Features: Demographic, professional, compensation, and satisfaction metrics

Target Variable: PerformanceRating

Target Classes:

2 → Low Performance

3 → Good Performance

4 → Excellent Performance

## 🔷 Tech Stack

Programming Language

Python

Libraries & Tools

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

Machine Learning Techniques

Classification Algorithms

Feature Encoding

Model Evaluation Metrics

## 🔷 Project Workflow
### 1️⃣ Data Understanding

Inspected dataset structure and data types

Checked missing values

Analyzed class distribution

### 2️⃣ Exploratory Data Analysis (EDA)

Correlation analysis

Distribution plots

Performance segmentation by department, role, and experience

Identification of influential features

### 3️⃣ Data Preprocessing

Label Encoding / One-Hot Encoding

Feature scaling (where required)

Train-test split (80/20)

### 4️⃣ Model Development

Implemented multiple classification models:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

### 5️⃣ Model Evaluation

Evaluated models using:

Accuracy Score

Compared model performance to identify the best-performing algorithm.

## 🔷 Key Insights

Job satisfaction and environment satisfaction strongly impact performance ratings.

Years at company and total working experience influence classification outcomes.

Department and job role show measurable variation in performance trends.

Tree-based models demonstrate strong performance for structured HR data.

## 🔷 Model Performance Summary
Model	Accuracy (Approx.)
Logistic Regression	Competitive
Decision Tree	Good
Random Forest	Best Performing

(Random Forest typically provides better generalization due to ensemble learning.)

## 🔷 Repository Structure
INX-Employee-Performance/
│
├── CODE/
│   └── INX_Employee_Performance_Analysis_And_Prediction.ipynb
│   └── README
├── DATASET/
│   └── INX_Future_Inc_Employee_Performance_CDS_Project2_Data_V1.8.xls
│   └── README
└── README.md

## 🔷 How to Run

Clone the repository
git clone <repository-link>

Install dependencies
pip install pandas numpy matplotlib seaborn scikit-learn

Open Jupyter Notebook
jupyter notebook

Run the notebook file

## 🔷 Skills Demonstrated

Data Cleaning & Preprocessing

Exploratory Data Analysis

Feature Engineering

Classification Modeling

Model Comparison & Evaluation

Business Insight Generation

End-to-End Machine Learning Workflow

## 🔷 Future Improvements

Hyperparameter tuning using GridSearchCV

Cross-validation for better generalization

Feature importance ranking

Deployment using Flask or Streamlit

Dashboard integration for HR teams

## 🔷 Author

## Sai
### Graduate | Aspiring Data Scientist
### Focused on Machine Learning, Analytics, and Real-World Business Problems
