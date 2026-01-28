# Proactive Detection of Machinery Faults Using Predictive Analytics

## Project Overview
This project focuses on proactive detection of machinery faults using predictive analytics and machine learning techniques. The goal is to predict the likelihood and type of machine failure based on operational sensor data, enabling preventive maintenance and reducing unplanned downtime in manufacturing environments.

By analyzing temperature, rotational speed, torque, and tool wear metrics, the project identifies key failure drivers and builds classification models to estimate machine failure risk before breakdown occurs.

---

## Problem Statement
Modern manufacturing systems rely heavily on machinery operating at peak efficiency. Unexpected machine failures can lead to production delays, increased costs, and safety risks.

This project aims to answer:
- What factors contribute most to machine failure?
- How can we estimate the probability of machine failure?
- Which types of failures are most likely to occur?

---

## Data Source
The dataset used in this project is the **AI4I 2020 Predictive Maintenance Dataset**, a publicly available benchmark dataset widely used for predictive maintenance research.

- **Source:** UCI Machine Learning Repository  
- **Dataset:** AI4I 2020 Predictive Maintenance Dataset  
- **Link:** https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset  
- **Provider:** Stephan Matzka, Hochschule für Technik und Wirtschaft Berlin  

---

## Dataset Description
- **Records:** 10,000 observations  
- **Features:** 14 variables  
- **Target Variable:** Machine failure (binary) and failure type (multiclass)

### Key Features
- Air temperature (K)  
- Process temperature (K)  
- Rotational speed (rpm)  
- Torque (Nm)  
- Tool wear (minutes)  
- Product quality variants (Low / Medium / High)  
- Machine failure indicator  

The dataset is fully anonymized and suitable for supervised learning tasks.

---

## Methodology
1. Data cleaning and preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature engineering and selection  
4. Binary classification modeling (failure vs no failure)  
5. Multiclass classification modeling (failure type prediction)  
6. Model evaluation and comparison  

---

## Models Implemented
### Binary Classification
- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- Gradient Boosting  

### Multiclass Classification
- Multinomial Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting  

---

## Model Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

Model performance is compared to identify the most reliable and interpretable predictive models.

---

## Key Insights
- Tool wear and torque emerged as strong predictors of machine failure
- Ensemble models (Random Forest, Gradient Boosting) consistently outperformed linear models
- Multiclass failure prediction required careful handling of class imbalance
- Predictive maintenance models can significantly reduce unplanned breakdown risk when deployed proactively

---

## Tools & Technologies
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## Repository Structure
predictive-maintenance-analytics/

├── notebooks/ # EDA, binary and multiclass modeling

└── README.md

## Why This Project Matters
This project demonstrates how predictive analytics and machine learning can be applied to real-world industrial data to prevent equipment failures, improve operational efficiency, and support data-driven maintenance strategies in manufacturing systems.
