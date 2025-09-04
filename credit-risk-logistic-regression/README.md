# German Credit Risk Prediction (Logistic Regression)

## 📌 Project Overview
Credit scoring is an essential tool in financial institutions to evaluate the risk of lending to customers.  
In this project, we use **Logistic Regression** to predict whether a customer is a **good credit risk** or a **bad credit risk** based on various features.

---

## 🎯 Objectives
- Predict the probability of loan default
- Identify key factors influencing credit risk
- Evaluate model performance using classification metrics

---

## 📊 Dataset
- Source: UCI German Credit Data
- Records: 1000 customers
- Features include: Age, Sex, Job, Housing, Credit Amount, Duration, Purpose, etc.
- Target: `Good` or `Bad` credit risk

---

## ⚙️ Methodology
1. Data Cleaning & Encoding  
2. Train-Test Split  
3. Logistic Regression Model  
4. Model Evaluation (Accuracy, Precision, Recall, Confusion Matrix)

---

## 📈 Results
- **Accuracy:** ~70% (depending on preprocessing)  
- Confusion matrix shows the balance between predicting good and bad credit risk.  
- Logistic Regression provides interpretability, highlighting which features impact credit risk.

---

## 🚀 How to Run
```bash
pip install -r ../requirements.txt
jupyter notebook German_Credit_Logistic_Regression.ipynb
```

---

## 📝 Future Improvements
- Try ensemble models (Random Forest, XGBoost, LightGBM)  
- Perform feature selection to improve accuracy  
- Explore deep learning approaches for credit scoring  
