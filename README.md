# credit-card-detection
A machine learning project to detect fraudulent credit card transactions using Python and popular data science libraries such as NumPy, Pandas, and Scikit-learn. The goal is to build an efficient classification model that can accurately identify fraud while minimizing false positives.

Credit card fraud detection 💳🔍 is the process of identifying suspicious or unauthorized credit card transactions in real time. It analyzes spending patterns 💳📊, transaction amounts 💰, locations 🌍, and time ⏰ using rules and machine learning 🤖. When a transaction looks unusual ⚠️, it is flagged or blocked instantly 🚫💳, helping banks and customers stay safe from financial loss 🔐💳.

---

## Project Overview

Credit card fraud is a major financial threat worldwide. This project applies supervised machine learning techniques to detect fraudulent transactions based on transaction data. The dataset is highly imbalanced, and special techniques are used to handle this imbalance and improve model performance.

---

## Features

- Data cleaning and preprocessing  
- Handling class imbalance using sampling techniques  
- Feature scaling and transformation  
- Multiple machine learning models  
- Model evaluation using standard classification metrics  
- Performance visualization (Confusion Matrix, ROC, Precision-Recall Curve)

---

##  Technologies & Libraries Used

- **Python**
- **NumPy**
- **Pandas**
- **Scikit-learn**
- **Matplotlib / Seaborn**
- **Imbalanced-learn (SMOTE / Under-sampling)**

---
## Dataset Information

- Source: Kaggle Credit Card Fraud Dataset  
- Total Transactions: 284,807  
- Fraudulent Transactions: 492  
- Features: 30 (V1–V28, Time, Amount, Class)  
- Target Variable: `Class`  
  - `0` → Legitimate  
  - `1` → Fraud  

> The dataset is highly imbalanced, making it a challenging classification task.

---

##  Installation & Setup

1. **Clone the repository**
```bash
git clone https://github.com/your-username/credit-card-fraud-detection.git
cd credit-card-fraud-detection
