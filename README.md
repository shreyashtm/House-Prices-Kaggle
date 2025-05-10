# 🏡 House Prices Prediction (Kaggle)

This project predicts house sale prices using advanced regression models, focusing on Random Forest and XGBoost. It is based on the [Kaggle House Prices - Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/) competition.

---

## 📁 Project Structure

- `notebook.ipynb`: Complete workflow including EDA, preprocessing, modeling, and evaluation
- `submission.csv`: Final predictions submitted to Kaggle
- `README.md`: Project overview and insights

---

## 🔍 Problem Statement

Predict the final sale price of homes in Ames, Iowa using various numeric and categorical features provided in the dataset.

---

## ⚙️ Tools & Libraries

- Python (Pandas, NumPy, Seaborn, Matplotlib)
- Scikit-learn
- RandomForestClassifier
- XGBoost
- Jupyter Notebook

---

## 🧹 Data Preprocessing

- Handled missing values using mean or median based on skewness
- Applied log transformation on the target (`SalePrice`) to reduce skew and improve model performance
- Performed feature selection based on correlation analysis

---

## 📊 Model Evaluation

| Model         | MAE       | MSE           | R²     |
|---------------|-----------|---------------|--------|
| Random Forest | 23,621.41 | 1,256,966,670 | 0.8206 |
| XGBoost       | 17,423.04 |   675,057,640 | 0.9036 |

✅ **XGBoost performs better**, offering lower error rates and higher explanatory power for predicting house prices.

---

## ✅ Kaggle Submission

- **XGBoost Submission RMSE**: `0.15373`  
- Score indicates strong generalization on unseen test data

---

## 🚀 How to Run

1. Clone this repository
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
