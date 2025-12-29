# Medical-Insurance-Cost-Prediction
This project predicts medical insurance charges using machine learning models based on demographic and lifestyle factors. It includes data cleaning, feature engineering, model comparison, evaluation, and explainability. Linear Regression achieved the best performance with strong accuracy.

# Medical Insurance Cost Prediction 💊📊

## 📌 Project Overview
This project aims to predict medical insurance charges based on demographic and lifestyle attributes using machine learning regression models.

The goal is to analyze key cost-driving factors and build an accurate predictive system for healthcare insurance expenses.

---

## 📂 Dataset
- Source: Kaggle – Medical Insurance Dataset
- Records include:
  - Age
  - Gender
  - BMI
  - Number of children
  - Smoking status
  - Region
  - Medical charges (target)

---

## 🔍 Exploratory Data Analysis (EDA)
Key insights discovered:
- Medical charges are heavily right-skewed
- Smoking is the strongest driver of insurance cost
- Age and BMI show positive correlation with charges

<p align="center">
  <img src="images/eda_univariate.png" width="400">
  <img src="images/eda_bivariate.png" width="400">
</p>

---

## 🛠️ Data Preprocessing
- Missing value check
- Outlier handling using IQR capping
- Log transformation of target variable
- One-hot encoding for categorical features
- Train-test split (80/20)

---

## 🤖 Models Trained
- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regressor
- Support Vector Regressor (RBF)

---

## 📊 Model Performance Comparison

| Model | MAE | RMSE | R² |
|------|----|----|----|
| Linear Regression | — | — | — |
| Ridge Regression | — | — | — |
| Lasso Regression | — | — | — |
| Random Forest | — | — | — |
| **Random Forest (Tuned)** | **Best** | **Best** | **Best** |

---

## 🏆 Final Model
**Tuned Random Forest Regressor** was selected due to superior performance and robustness in capturing nonlinear relationships.

---

## ⚠️ Limitations
- Small dataset size
- Lack of medical history features

---

## 🚀 Future Work
- Gradient Boosting (XGBoost)
- Model deployment using Streamlit
- Larger healthcare datasets

---

## 🧠 Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 👩‍💻 Author
Menna Mohammed
