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
* Distribution of all features
<img width="1489" height="290" alt="dist1" src="https://github.com/user-attachments/assets/4e09448b-174c-438a-a026-f2093536bcb2" />
<img width="1481" height="290" alt="dist2" src="https://github.com/user-attachments/assets/85307340-9c7e-4321-9fc7-97daddad1336" />
<img width="1489" height="290" alt="dist3" src="https://github.com/user-attachments/assets/29f57a5a-ddaa-4e2b-b462-51e1cb73ed8c" />
<img width="1489" height="290" alt="dist4" src="https://github.com/user-attachments/assets/b3f6efd8-7289-45dd-93d2-021a0eaf6a5a" />
<img width="1489" height="290" alt="distt5" src="https://github.com/user-attachments/assets/61260693-8208-4749-9d3e-40ef5bf06ecd" />
<img width="1489" height="290" alt="dist6" src="https://github.com/user-attachments/assets/eaabbe89-44c5-46fe-87e8-17fcfe1d4531" />
* Correlation between Term and other features
  <img width="1175" height="841" alt="corr" src="https://github.com/user-attachments/assets/39f38301-b6ac-4bbd-853b-2985670e6c10" />
📝 Key Findings

* Profit scoring provides better lender returns than traditional credit scoring.
  📌 Future Enhancements
* Incorporate time-based survival modeling (Cox PH)

* Add macroeconomic variables for more realistic profit forecasting

* Build a dashboard to visualize risk-return trade-offs

* Deploy a simple API for profit scoring predictions


If you have questions or ideas, feel free to reach out!
