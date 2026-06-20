# Fairness, Bias and Explainability Analysis of Customer Churn Prediction

## Overview

This project evaluates the fairness, bias, and explainability of a customer churn prediction model using SHAP and demographic fairness analysis.

Techniques Used:

* Random Forest Classifier
* SHAP Explainability
* Feature Importance Analysis
* Fairness Assessment

Groups Analyzed:

* Gender
* Senior Citizens

---

## Dataset

Dataset File:

WA_Fn-UseC_-Telco-Customer-Churn.csv
[https://www.kaggle.com/datasets/blastchar/telco-customer-churn?](url)

Place the dataset in the same directory as the notebook before execution.

---

## Environment Setup

### Create Virtual Environment (Optional)

```bash
python -m venv venv
```

Activate environment:

Windows:

```bash
venv\Scripts\activate
```

Linux/Mac:

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn shap jupyter
```

---

## Run Notebook

```bash
jupyter notebook
```

Open:

```text
Task4_Fairness_Bias_Explainability.ipynb
```

Run all cells sequentially.

---

## Outputs

* Feature Importance Plot
* SHAP Summary Plot
* SHAP Bar Plot
* Individual Prediction Explanation
* Gender Fairness Analysis
* Senior Citizen Fairness Analysis
* Bias Assessment Report
* Mitigation Recommendations

---

## Author

Jiya Arora
