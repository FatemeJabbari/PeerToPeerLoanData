In this project, I have used Prosper loan dataset contains 113,937 loans with 81 variables on each loan, including loan amount, borrower rate (or interest rate), current loan status, borrower income, and many others.
This project, goes beyond peer-to-peer (P2P) lending credit scoring systems by proposing a profit scoring. Credit scoring systems estimate loan default probability.
# Prosper Loan Profit Scoring
Analyzing Prosper’s peer-to-peer loan dataset to estimate default probability and introduce a profit scoring system.

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)]()
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)]()

---

## 📌 Project Overview

In this project, I analyze the **Prosper Loan dataset**, which contains:

- **113,937 loans**
- **81 variables** per loan  
- Rich borrower characteristics such as income, loan amount, credit history, borrower rate (interest rate), loan term, loan status, and more.

Traditional peer-to-peer (P2P) lending models focus on **credit scoring**, which estimates the **probability of default (PD)**.

👉 **This project goes further.**  
Instead of only predicting default, it proposes a **profit scoring model**, integrating:

- Default probability  
- Interest earnings  
- Expected financial return  
- Risk-adjusted loan prioritization  

The goal is to help lenders **maximize profit**, not just minimize default.

---

## 🎯 Objectives

- Perform data cleaning and exploratory data analysis  
- Understand borrower characteristics affecting loan performance  
- Estimate **probability of default (PD)** using various statistical models  
- Design a **profit scoring system** that integrates default risk and expected return  
- Compare profit scoring vs. traditional credit scoring  

---

## 📁 Dataset Description

The Prosper dataset includes the following categories of data:

### Borrower Information  
Income range, employment status, credit score, debt-to-income ratio, home ownership.

### Loan Details  
Loan amount, term, borrower rate (interest rate), monthly payment, loan purpose.

### Loan Performance  
Loan status (Current, Defaulted, Charged-off), payments, delinquency, credit line history.

### Credit & Risk Features  
Credit lines, delinquencies, inquiries, public records, credit grade assigned by Prosper.

---

## 🧰 Tools & Libraries Used

| Purpose | Libraries |
|--------|-----------|
| Data analysis | `pandas`, `numpy` |
| Visualization | `matplotlib`, `seaborn` |
| Machine learning | `scikit-learn` |
| Statistical modeling | `statsmodels` |
| Jupyter Notebooks | For interactive analysis |

---

Modeling Approaches

1. Probability of Default Models

* Logistic Regression

* Multivariate Linear Regression

Metrics used:

* Precision-Recall

* Confusion Matrix

* Classification report

2. Profit Scoring Framework
* Desicion Tree
  
📊 Key Visualizations
