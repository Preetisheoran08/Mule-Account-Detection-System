# Mule Account Detection System

## Overview
This project was developed as part of the **RBIH × IIT Delhi TRYST National Challenge** to identify mule accounts involved in fraudulent financial activities. The objective was to build a machine learning solution capable of detecting suspicious banking accounts using large-scale transaction data.

The project involved extensive data preprocessing, feature engineering, exploratory data analysis, and predictive modeling to improve fraud detection performance.


## Problem Statement
Mule accounts are bank accounts used to transfer or launder illegally obtained funds. Detecting such accounts is crucial for strengthening anti-money laundering (AML) systems and preventing financial fraud.

The goal of this project was to classify accounts as either:
- **Mule Account (Fraudulent)**
- **Legitimate Account**



## Dataset

The dataset consisted of multiple banking-related tables, including:

- Customer Information
- Account Details
- Customer–Account Linkage
- Product Information
- Transaction Records
- Training Labels

### Dataset Size
- Approximately **16.2 GB**
- Over **400 million transaction records**



## Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- Polars
- Scikit-learn
- Matplotlib
- Seaborn

### Machine Learning Models
- LightGBM
- XGBoost
- CatBoost
- Random Forest
- Logistic Regression
- Ensemble Techniques


## Methodology

### 1. Data Integration
Merged multiple datasets to create a unified analytical view of customer behavior.

### 2. Data Preprocessing
- Missing value handling
- Data type conversion
- Label encoding
- Feature cleaning

### 3. Feature Engineering
Engineered **50+ Anti-Money Laundering (AML) features**, including:

- Transaction frequency patterns
- Transaction amount statistics
- Temporal behavioral indicators
- Customer-account relationship metrics
- Product usage characteristics

### 4. Exploratory Data Analysis
Performed EDA to understand:
- Class imbalance
- Transaction distributions
- Customer behavior trends

### 5. Model Development
Trained and evaluated multiple machine learning models using **5-fold cross-validation**.

### 6. Ensemble Learning
Combined predictions from several high-performing models to improve robustness and predictive performance.



## Results

- Achieved an **AUC-ROC score of 0.9441**
- Successfully identified suspicious transaction patterns associated with mule accounts.
- Improved fraud detection capability through feature engineering and ensemble modeling.



## Repository Structure

```
├── Fraud_Prevention.ipynb
├── README.md
├── requirements.txt
└── docs/
```



## Future Improvements

- Real-time fraud detection pipeline
- Graph-based fraud analytics
- Explainable AI techniques (SHAP/LIME)
- Deployment using cloud infrastructure
