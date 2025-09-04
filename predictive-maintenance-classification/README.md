# Predictive Maintenance Classification

## 📌 Project Overview
This project applies **machine learning** to predict equipment failures in advance, enabling proactive maintenance strategies.  
By analyzing sensor data, we classify whether a machine is operating normally or at risk of failure.

---

## 🎯 Objectives
- Predict equipment failure using classification algorithms  
- Identify important features that contribute to failures  
- Improve maintenance planning with predictive analytics  

---

## 📊 Dataset
- Contains sensor data such as: Air temperature, Process temperature, Torque, Rotational speed, Tool wear
- Target: `0` = Normal operation, `1` = Failure  

---

## ⚙️ Methodology
1. Data cleaning and preprocessing  
2. Train-test split  
3. Random Forest classifier for prediction  
4. Model evaluation with classification metrics  

---

## 📈 Results
- **Accuracy:** High (>90%) depending on preprocessing  
- Feature importance highlights key failure indicators  
- Confusion matrix shows classification performance  

---

## 🚀 How to Run
```bash
pip install -r ../requirements.txt
jupyter notebook Predictive_Maintenance_Classification.ipynb
```

---

## 📝 Future Improvements
- Test alternative models (XGBoost, LightGBM, Neural Networks)  
- Use real-time streaming data for online predictions  
- Implement cost-based optimization for maintenance scheduling  
