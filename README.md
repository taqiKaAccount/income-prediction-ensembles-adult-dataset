## Overview

This repository contains a supervised learning and model evaluation project using the **Adult (Census Income) dataset** from the UCI Machine Learning Repository(https://archive.ics.uci.edu/dataset/20/census+income).  
The objective is to predict whether an individual earns more than \$50K per year based on demographic and employment-related attributes, while analyzing model performance, ensemble improvements, and ethical implications.

The project covers end-to-end data science workflows including exploratory data analysis, feature engineering, supervised classification models, ensemble learning, and fairness-oriented reflection.

I'd like to acknowledge my partner in this project: [Shayaan Qazi](https://github.com/shayaanhu)

---
## Dataset

**Name:** Adult / Census Income Dataset  
**Source:** UCI Machine Learning Repository (1994 U.S. Census data)  
**Target Variable:** Income (`<=50K`, `>50K`)

**Description:**  
The dataset contains demographic and socio-economic attributes such as age, education, marital status, occupation, race, sex, hours worked per week, and native country.  
It is widely used to study supervised learning, bias, and fairness in machine learning.

---

## Methodology

### 1. Data Understanding & EDA
- Data cleaning and handling missing values
- Distribution analysis of numeric and categorical features
- Income distribution across demographic groups
- Correlation and dependency exploration

### 2. Feature Engineering
- Encoding categorical variables
- Scaling numeric features where required
- Feature selection and relevance analysis

### 3. Supervised Models

#### Decision Trees
- ID3 (Information Gain)
- CART (Gini Index)
- Hyperparameter tuning (max depth, pruning)
- Complexity vs performance analysis

#### K-Nearest Neighbors
- Multiple distance metrics:
  - Euclidean
  - Manhattan
  - Cosine
- Comparison of distance-based behavior

### 4. Ensemble Methods

#### Tree-Based Ensembles
- Bagging (Bootstrap Aggregating)
- Boosting (AdaBoost / Gradient Boosting / XGBoost)

#### KNN Ensembles
- Distance-weighted voting
- Random subspace KNN ensembles

Performance of ensemble models is compared against single-model baselines.

---

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

Results are reported consistently across models to enable fair comparison.

---

## Model Interpretation
- Feature importance analysis
- Comparison of split criteria and distance metrics
- Analysis of ensemble gains over single learners

---

## Social & Ethical Reflection

This project critically examines the implications of income prediction using census data:

- Bias analysis across gender, race, and education levels
- Risks of reinforcing socio-economic inequalities
- Trade-offs between accuracy, interpretability, and fairness
- Discussion of bias mitigation strategies (e.g., sampling, feature review, fairness-aware metrics)

The reflections are linked to relevant **UN Sustainable Development Goals (SDGs)**:
- Reduced Inequalities (SDG 10)
- Decent Work and Economic Growth (SDG 8)
- Gender Equality (SDG 5)

---

## Tools & Libraries
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## Reproducibility
All experiments are reproducible.  
Random seeds are fixed where applicable, and preprocessing steps are documented within the notebook.
