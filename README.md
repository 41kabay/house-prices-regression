# 🏡 House Prices Prediction — Kaggle Competition  

> **Author:** Timur Kim  
> Student at Constructor University | Interested in Machine Learning, Deep Learning, and Quantitative Finance  

---

## 📘 Overview  

This repository contains my **first full end-to-end machine learning project**, created as part of my learning journey in Data Science and Machine Learning.  
It is based on the [Kaggle competition “House Prices — Advanced Regression Techniques”](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques).  

The goal is to **predict the final sale price of residential homes** in Ames, Iowa, using various numerical and categorical features describing each house.  

This project demonstrates my understanding of:
- Exploratory Data Analysis (EDA)  
- Data preprocessing and feature engineering  
- Building and evaluating regression models  
- Submitting predictions to Kaggle  

---

## 🧠 Key Learnings  

- Handling missing values (categorical → `"None"`, numerical → median)  
- Encoding categorical variables using `pd.get_dummies()`  
- Understanding multicollinearity and regularization (Ridge, Lasso)  
- Evaluating models with RMSLE (Root Mean Squared Logarithmic Error)  
- Structuring an end-to-end ML workflow from raw data to submission  
- Working with GitHub and Jupyter Notebook for reproducible ML research  

---

## ⚙️ Tech Stack  

| Category | Tools |
|-----------|--------|
| Language | Python |
| Environment | Jupyter Notebook |
| Libraries | pandas, numpy, matplotlib, seaborn, scikit-learn |
| Platform | Kaggle |
| Version Control | Git & GitHub |

---

## 🚀 How to Run  

1. **Clone the repository:**
   ```bash
   git clone https://github.com/TimurKim/house-prices-regression.git
   cd house-prices-regression
📁 Project Structure
house-prices-regression/
│

├── house_price.ipynb          # main notebook

├── requirements.txt           # dependencies

├── submission.csv             # sample submission file

├── README.md                  # project description

└── .gitignore                 # ignored files (data, checkpoints)

🔮 Future Improvements

Implement ensemble methods (XGBoost, LightGBM, CatBoost)

Add cross-validation and grid search for hyperparameter tuning

Apply log transformation to target and selected skewed features

Deploy a small Streamlit web app for interactive house price predictions

