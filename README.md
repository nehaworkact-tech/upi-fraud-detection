# UPI Payment Fraud Detection System

## Project Overview
An end-to-end machine learning project to detect fraudulent UPI 
payment transactions in real time. Built as a portfolio project 
to demonstrate full-stack data science skills in the BFSI domain.

---

## Problem Statement
UPI processes 14+ billion transactions monthly in India. Fraud 
detection is the #1 data science challenge for every bank, 
fintech, and payment company. This project builds a system that:
- Identifies fraudulent transactions instantly
- Explains why a transaction was flagged (RBI compliance)
- Quantifies business value saved
- Enables risk-based decisions: Block / Review / Allow

---

## Project Objectives
1. Build an end-to-end model following industry CRISP-DM framework
2. Solve a real problem valued in Indian BFSI market
3. Compare statistical, ML, and deep learning approaches
4. Rationalize every decision with industry-level thinking

---

## Dataset
**IEEE-CIS Fraud Detection Dataset** (Kaggle)
- 590,000 real anonymised transactions
- Proxy for UPI transaction data (proprietary data not publicly available)
- Methodology mirrors fraud detection systems at Indian fintechs and banks

---

## Models Built
### Supervised (Labelled Fraud Data)
| Model | Purpose |
|---|---|
| Logistic Regression | Baseline + interpretability |
| LightGBM | Fast, production-grade gradient boosting |
| XGBoost + SHAP | Best performance + explainability |

### Unsupervised (Anomaly Detection)
| Model | Purpose |
|---|---|
| Isolation Forest | Catches unknown fraud patterns |
| AutoEncoder | Deep learning reconstruction error |

### Deep Learning
| Model | Purpose |
|---|---|
| Neural Network | Feedforward fraud classifier |

---

## Project Structure
```
upi-fraud-detection/
├── data/                          # Raw dataset files
├── notebooks/                     # Jupyter notebooks (CRISP-DM)
│   ├── 01_business_understanding
│   ├── 02_eda
│   ├── 03_data_prep
│   ├── 04_feature_engineering
│   ├── 05_imbalance_handling
│   ├── 06_logistic_regression
│   ├── 07_lightgbm
│   ├── 08_xgboost_shap
│   ├── 09_isolation_forest
│   ├── 10_autoencoder
│   ├── 11_neural_network
│   ├── 12_model_comparison
│   └── 13_business_output
├── src/                           # Reusable functions
├── outputs/                       # Charts, model files, reports
└── README.md
```

---

## Key Technical Decisions & Rationale
*(This section will be updated as the project progresses)*

- **Why IEEE-CIS dataset:** Most respected public fraud dataset,
  mirrors UPI transaction structure, used as industry benchmark
- **Why Precision-Recall over ROC-AUC:** With 0.1% fraud rate,
  ROC is misleading — PR curve shows real model performance
- **Why SHAP:** RBI regulations require explainability — 
  black box models are not acceptable in Indian banking

---

## Timeline
| Week | Focus |
|---|---|
| 1 | Business understanding + EDA |
| 2 | Data prep + feature engineering |
| 3 | Imbalance handling + Logistic Regression + LightGBM |
| 4 | XGBoost + SHAP + Isolation Forest |
| 5 | AutoEncoder + Neural Network + Model Comparison |
| 6 | Business output + Streamlit dashboard + final polish |

---

## Author
**Neha Oraon**
Data Scientist | 5+ years BFSI domain experience
[https://www.linkedin.com/in/neha-oraon-3011/] | [neha.work_act@gmail.com]
