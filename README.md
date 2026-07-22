# 🛡️ Network Intrusion Detection using Machine Learning

## Machine Learning Classification of Network Attacks with CICIDS-2017 Dataset

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange)
![Power BI](https://img.shields.io/badge/Power-BI-yellow)
![Cybersecurity](https://img.shields.io/badge/Cybersecurity-NIST-red)

---

## 📌 Project Overview

This project develops a machine learning-based Network Intrusion Detection System (NIDS) to identify malicious network activities and classify cyber threats.

The project compares multiple machine learning classification algorithms under imbalanced and SMOTE-balanced dataset conditions.

The final solution combines:

- Machine Learning models
- Data preprocessing
- Feature engineering
- Model evaluation
- Power BI visual analytics
- NIST Cybersecurity Framework mapping

---

# 🎯 Objectives

The main objectives are:

- Detect malicious network traffic
- Compare classification algorithms
- Handle class imbalance using SMOTE
- Evaluate model performance
- Translate technical findings into cybersecurity recommendations

---

# 📂 Dataset

## CICIDS-2017 Dataset

Source:

Canadian Institute for Cybersecurity (CIC)

The dataset contains realistic network traffic including:

- BENIGN traffic
- DoS attacks
- DDoS attacks
- Brute Force attacks
- Web attacks
- Infiltration attacks
- Botnet traffic

The original dataset is not included due to GitHub size limitations.

Dataset details:

📁 [Dataset Documentation](data/README.md)

---

# 🏗️ Project Architecture

```
Raw Network Traffic Data

        ↓

Data Cleaning & Preprocessing

        ↓

Exploratory Data Analysis

        ↓

Feature Engineering

        ↓

SMOTE Class Balancing

        ↓

Machine Learning Models

        ↓

Performance Evaluation

        ↓

Power BI Security Dashboard

        ↓

Business Recommendations
```

---

# 🤖 Machine Learning Models

The following classification algorithms were evaluated:

## 1. Logistic Regression

Used as a baseline classification model.

## 2. Decision Tree

Evaluated for interpretable security classification.

## 3. Random Forest

Selected as the final model due to strong classification performance.

---

# ⚙️ Data Processing Workflow

The workflow includes:

- Data cleaning
- Missing value treatment
- Duplicate removal
- Feature selection
- Label encoding
- Data normalisation
- SMOTE balancing
- Model training and testing

---

# 📊 Model Performance

| Model | Accuracy | Status |
|---|---|---|
| Logistic Regression | TBD | Baseline |
| Decision Tree | TBD | Evaluated |
| Random Forest | 99.52% | ⭐ Best Model |

---

# 🛡️ NIST Cybersecurity Framework Mapping

Model outcomes were mapped against NIST Cybersecurity Framework 2.0:

| Function | Application |
|-|-|
| Identify | Understanding network risks |
| Protect | Preventing security threats |
| Detect | Identifying malicious traffic |
| Respond | Supporting incident response |
| Recover | Improving security resilience |

---

# 📊 Power BI Dashboard

The dashboard provides:

- Attack distribution analysis
- Model performance comparison
- Traffic classification insights
- Feature importance analysis
- Cybersecurity recommendations

Dashboard pages:

- Security Overview
- Attack Analysis
- Model Performance
- Strategic Insights

---

# 📁 Repository Structure

```
network-intrusion-detection-ml

├── data
├── notebooks
├── powerbi
├── reports
└── README.md
```

---

# 🛠️ Technologies Used

## Programming

- Python
- Pandas
- NumPy

## Machine Learning

- Scikit-learn
- Random Forest
- Decision Tree
- Logistic Regression
- SMOTE

## Analytics

- Power BI
- SQL
- Data Visualisation

---

# 💼 Business Value

This project demonstrates how machine learning can support organisations by:

- Improving threat detection capability
- Reducing manual security monitoring effort
- Supporting risk-based decision-making
- Providing actionable cybersecurity insights

---

# 👨‍💻 Author

**Vikash Sharma**

Business Analyst | Data Analytics | Business Informatics

GitHub:
https://github.com/vikash-sharma-nz

LinkedIn:
https://www.linkedin.com/in/vikashinu
