# Telco Customer Churn Prediction

This project focuses on predicting customer churn for a telecommunications company using machine learning techniques. By identifying customers at risk of leaving, the business can take proactive retention measures, thereby reducing costs and increasing profitability.

## 🎯 Project Goal
Customer retention is a critical metric for subscription-based businesses. The primary objectives of this project are:
- To analyze customer data and identify key factors driving churn.
- To build predictive models that can classify customers as "likely to churn" or "loyal".
- To provide actionable business insights based on data analysis.

## 📊 Dataset
**Source:** [Telco Customer Churn (Kaggle)](https://www.kaggle.com/blastchar/telco-customer-churn)
- **Rows:** 7043 customers
- **Features:** 21 columns including demographics, account information, and service details.
- **Target Variable:** `Churn` (Yes/No)

## 🗂 Project Structure
The project follows the Cookiecutter Data Science standard:


├── data
│   ├── raw            # Original, immutable data dump
│   └── processed      # The final, canonical data sets for modeling
├── notebooks          # Jupyter notebooks for exploration and analysis
├── src                # Source code for use in this project
├── models             # Trained and serialized models
└── README.md          # The top-level README for developers using this project

## 🚀 Installation & Usage
Clone the repository:

```Bash
git clone [https://github.com/bedirhankaraahmetli/churn-prediction.git](https://github.com/bedirhankaraahmetli/churn-prediction.git)

cd churn-prediction
```

Create a virtual environment:

```Bash
## Windows
python -m venv .venv
.\.venv\Scripts\activate

## Mac/Linux
python3 -m venv .venv
source .venv/bin/activate
```

Install dependencies:

```Bash
pip install -r requirements.txt

```

## 📈 Roadmap
[x] Project Setup & Data Loading

[ ] Phase 1 (Beginner): Exploratory Data Analysis (EDA) & Baseline Logistic Regression Model

[ ] Phase 2 (Intermediate): Feature Engineering, Handling Class Imbalance (SMOTE), and Tree-based Models (Random Forest/XGBoost)

[ ] Phase 3 (Advanced): Model Deployment (Streamlit) and API Integration

This project is developed for educational and portfolio purposes.