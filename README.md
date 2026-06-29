# Customer Churn Prediction & Business Analytics

## Project Overview

Customer churn is one of the most important business problems in subscription-based industries such as telecommunications.

This project analyzes customer behaviour and predicts churn using exploratory data analysis (EDA), SQL analytics, visualization, and machine learning.

The objective is to identify patterns that contribute to customer loss and generate actionable business recommendations.

---

## Problem Statement

Customer acquisition is expensive.

Retaining existing customers is often more cost-effective than acquiring new ones.

This project attempts to answer:

- Which customers are likely to churn?
- What factors contribute most to churn?
- How can businesses reduce customer loss?

---

## Dataset

Dataset:
IBM Telco Customer Churn Dataset

Source:
https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Dataset contains customer information including:

- Demographics
- Contract details
- Billing information
- Service subscriptions
- Customer churn status

Target Variable:

```text
Churn
```

---

## Project Structure

```text
customer-churn-project/

data/
│
├── raw/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv
│
├── cleaned/
│   └── cleaned_customer_churn.csv

notebooks/
│
├── 01_cleaning.ipynb
├── 02_eda.ipynb
├── 03_model.ipynb

sql/
│
└── churn_queries.sql

dashboard/

README.md
requirements.txt
```

---

## Objectives

### Data Cleaning
- Handle missing values
- Convert incorrect datatypes
- Remove duplicate records

### Exploratory Data Analysis
- Analyze churn distribution
- Study contract effects
- Evaluate customer spending behaviour
- Understand customer retention patterns

### Machine Learning
- Predict customer churn
- Compare model performance
- Identify influential variables

### Business Analytics
- Translate findings into business actions

---

## Technologies Used

### Programming
- Python

### Libraries
- pandas
- numpy
- matplotlib
- scikit-learn

### Analytics
- SQL

### Visualization
- Power BI

---

## Workflow

```text
Raw Data
↓
Data Cleaning
↓
EDA
↓
SQL Analysis
↓
Machine Learning
↓
Business Recommendations
↓
Dashboard
```

---

## Data Cleaning Steps

Completed:

- Loaded raw dataset
- Converted TotalCharges to numeric
- Removed missing values
- Removed duplicates
- Reset index
- Saved cleaned dataset

---

## Exploratory Data Analysis

Business questions investigated:

1. What percentage of customers churn?

2. Which contract type experiences highest churn?

3. Does monthly charge influence churn?

4. Are senior citizens more likely to churn?

5. Does customer tenure affect retention?

6. Which payment methods retain customers?

---

## Machine Learning Models

Planned:

- Logistic Regression
- Random Forest
- XGBoost (Optional)

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

---

## Dashboard

Dashboard includes:

- Customer overview
- Churn distribution
- Contract analysis
- Revenue indicators
- Customer segmentation

---

## Key Insights

(To be updated after EDA)

- Insight 1
- Insight 2
- Insight 3

---

## Business Recommendations

(To be updated after analysis)

Example:

- Encourage long-term contracts
- Target high-risk customers
- Improve retention strategies

---

## Future Improvements

- Hyperparameter tuning
- Feature engineering
- Deployment using Streamlit
- Real-time prediction pipeline

---

## Author

Eeshani Chakraborty

M.Sc. Data Science (2026)
