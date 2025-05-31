# 🚗 Vehicle Insurance Claim Fraud Detection

This project applies machine learning techniques to detect fraudulent vehicle insurance claims using a real-world dataset. The goal is to accurately identify fraud cases in an imbalanced dataset, improving fraud detection efficiency and minimizing false positives.

---

## 📊 Overview

- **Objective:** Detect fraudulent claims from vehicle insurance data.
- **Dataset Size:** 15,420 records, 33 features
- **Target Variable:** `FraudFound_P` (Binary: Fraud/Not Fraud)
- **Challenge:** Highly imbalanced target (~6% fraud cases)

We use a combination of classical ML models, ensemble learning, neural networks, and sampling strategies to tackle the class imbalance and boost fraud detection performance.

---

## 📁 Dataset

- **Source:** [Kaggle Vehicle Claim Fraud Detection Dataset](https://www.kaggle.com/datasets)
- **File used:** `fraud_oracle.csv` (included in repository)
- **Features include:**
  - Policy & Claim information
  - Vehicle and driver details
  - Incident type and location
  - Repair and witness information

---

## ⚙️ Environment & Dependencies

- **OS:** macOS  
- **Python Version:** 3.11.5  
- **Hardware:** Apple M2 chip, 8 GB RAM  

### Required Libraries
```bash
pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
xgboost
lightgbm
catboost
tensorflow
torch
plotly 
```
📄 Read the full [Project Report](docs/Project_Report.pdf)

