# Anime Rating Prediction (Linear Regression)

## 📌 Project Overview
This project predicts anime ratings using **linear regression**.  
By analyzing features such as popularity, number of members, and genre, we aim to estimate how an anime is rated by viewers.

---

## 🎯 Objectives
- Predict anime ratings based on available attributes  
- Evaluate regression performance using MSE and R²  
- Explore the relationship between popularity and ratings  

---

## 📊 Dataset
- Features: Episodes, Genre, Popularity, Members, etc.  
- Target: Average rating (scale of 1–10)  

---

## ⚙️ Methodology
1. Data cleaning (handling missing values)  
2. Feature encoding  
3. Train-test split  
4. Linear regression model training  
5. Evaluation with MSE and R²  

---

## 📈 Results
- **R² Score:** Moderate (model explains part of the variance)  
- Scatter plot demonstrates actual vs predicted ratings  

---

## 🚀 How to Run
```bash
pip install -r ../requirements.txt
jupyter notebook Anime_Rating_Linear_Regression.ipynb
```

---

## 📝 Future Improvements
- Use ensemble regression models (Random Forest, Gradient Boosting)  
- Add NLP features from anime descriptions or reviews  
- Incorporate time-series trends for seasonal rating predictions  
