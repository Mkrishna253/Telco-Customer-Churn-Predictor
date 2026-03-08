
# 🚨 Telco Customer Churn Predictor

This repository presents a machine learning workflow for predicting telecom customer churn using customer profiles, usage patterns, and billing data. The project covers data cleaning, exploratory analysis, feature engineering, model training, and evaluation.

## ✨ Features
- End-to-end workflow from raw data to model evaluation
- Data cleaning and type fixes for billing features
- Categorical encoding (label + one-hot) and feature scaling
- Exploratory visualizations for churn patterns
- Random Forest model training and evaluation
- Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC

## 📝 Problem Statement
Customer churn leads to significant revenue loss for telecom companies. This project aims to automate the identification of high-risk customers and highlight key churn factors, enabling proactive retention strategies and improved business outcomes.

## 📂 Dataset
- Customer demographics
- Service details (Internet, Security, Tech Support)
- Contract and billing information
- Target: **Churn (Yes/No)**

## 🔧 Project Workflow
1. **Exploratory Data Analysis (EDA):** Assess class balance and visualize distributions
2. **Preprocessing:** Clean data, handle missing values, and fix types
3. **Feature Engineering:** Encode categorical variables and scale numeric features
4. **Model Training:** Train a Random Forest classifier
5. **Evaluation:** Report classification metrics and confusion matrix

## 🚀 Getting Started
1. Clone this repository
2. Install dependencies from `requirements.txt`
3. Ensure your dataset is available in the project directory
4. Run the notebook to reproduce results and visualizations

## 🛠️ Tech Stack
- Python - Pandas, NumPy - Scikit-learn - Matplotlib, Seaborn

## 📊 Results
The project benchmarks multiple models and provides detailed evaluation metrics. Visualizations help interpret model performance and dataset characteristics, supporting actionable business decisions.

## 📄 License
This project is provided for educational and research purposes. Please refer to the repository license for usage details.

## 🙏 Acknowledgements
- Scikit-learn documentation
- Open-source datasets and contributors
