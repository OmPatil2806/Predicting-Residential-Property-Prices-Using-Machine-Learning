# 🏠 Predicting Residential Property Prices Using Machine Learning  

---

## 📘 Project Overview  
This project focuses on **predicting residential property prices** using machine learning algorithms such as **Linear Regression** and **Random Forest Regressor**.  

It covers the **entire ML pipeline** — from **data exploration and feature engineering** to **model tuning and evaluation** — to uncover how property features like living area, quality, and age influence housing prices.

---

## ❓ Problem Statement  
Accurate **house price prediction** is vital for buyers, sellers, and investors to make data-driven decisions.  

This project applies **supervised machine learning** on historical housing data to estimate property values based on both **physical and qualitative features**, enabling **transparent and reliable real estate valuation**.

---

## ⚙️ Key Features  

- 📊 Comprehensive **Exploratory Data Analysis (EDA)** with rich visualizations  
- 🔧 **Missing value imputation** and **outlier detection**  
- 🧩 **Feature engineering** (e.g., TotalSF, Age, RemodAge, Bathrooms)  
- ⚙️ **Categorical encoding** & **feature scaling** via `ColumnTransformer`  
- 🤖 **Model comparison**: Linear Regression vs Random Forest Regressor  
- 🎯 **Hyperparameter tuning** using `RandomizedSearchCV`  
- 🔄 **Cross-validation** for model robustness  
- 💾 **Model persistence** using `joblib`  
- 📤 **Export final predictions** as a CSV file  

---

## 🚀 Project Workflow  

1️⃣ **Import Libraries**  
2️⃣ **Load and Clean Dataset**  
3️⃣ **Perform EDA** to uncover patterns and correlations  
4️⃣ **Engineer Features** – TotalSF, Age, RemodAge, Bathrooms, etc.  
5️⃣ **Preprocess Data** using pipelines (encoding + scaling)  
6️⃣ **Train Models** (Linear Regression, Random Forest Regressor)  
7️⃣ **Tune Models** with `RandomizedSearchCV`  
8️⃣ **Evaluate & Compare** using RMSE and R² metrics  
9️⃣ **Export Predictions** and save model artifacts  

---

## 💾 Artifacts  

| File Name | Description |
|------------|-------------|
| `house_price_best_rf.pkl` | Trained Random Forest model |
| `preprocessor.joblib` | Saved preprocessing pipeline |
| `Dataset.csv` | Original housing dataset |
| `house_price_predictions.csv` | Final predicted prices |

---

## 💡 Business Insights  

- 🏡 **Living area** and **overall quality** are the strongest predictors of sale price.  
- 🛠️ **Recently built or remodeled houses** tend to have higher values.  
- 🌳 **Random Forest Regressor** captures complex, non-linear relationships effectively.  
- 💰 The analysis supports **pricing strategy**, **investment assessment**, and **market forecasting**.  

---

## 🧠 Machine Learning Models Used  

| Model | Description | Evaluation Metric |
|--------|--------------|-------------------|
| **Linear Regression** | Baseline model to estimate linear relationships | RMSE |
| **Random Forest Regressor** | Ensemble model providing robust, non-linear predictions | RMSE, R² Score |

---

## 📊 Dataset  

**Dataset:** [House Prices – Advanced Regression Techniques (Kaggle)](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)  

**Key Features:**  
- LotArea, GrLivArea, OverallQual, YearBuilt, TotalBsmtSF, GarageCars, etc.  
- **Target Variable:** SalePrice  

---

## 🧰 Tools & Technologies  

| Category | Tools / Libraries |
|-----------|-------------------|
| **Programming Language** | Python 🐍 |
| **Data Manipulation** | pandas, numpy |
| **Visualization** | matplotlib, seaborn |
| **Machine Learning** | scikit-learn |
| **Model Persistence** | joblib |
| **Hyperparameter Tuning** | RandomizedSearchCV |

---

## 📈 Results Summary  

✅ **Random Forest Regressor** achieved the best performance in terms of **RMSE** and **R²** metrics.  
📊 The final tuned model demonstrated **high prediction accuracy** on unseen data.  
🏠 **Feature importance analysis** identified **living area, quality, and year built** as key predictors of property price.  

---

## 👤 Author  

**Om Patil**  
🎓 *Data Science & Machine Learning Enthusiast*  
🔗 [Connect with me on LinkedIn](https://www.linkedin.com/in/om-patil-039863369/)  
👨‍💻 [GitHub Profile](https://github.com/OmPatil2806)
