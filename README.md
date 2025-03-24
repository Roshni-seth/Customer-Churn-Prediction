# Customer Churn Prediction

## 📌 Project Overview
This project aims to predict customer churn using machine learning models. We performed feature engineering, explored the dataset, and trained multiple models to identify customers likely to leave.

## 📂 Dataset
The dataset consists of customer details, including demographic, account-related, and financial information. The target variable is **Exited** (1 = Churned, 0 = Retained).

## ⚙️ Feature Engineering
- **Dropped Unnecessary Columns:** Removed `RowNumber`, `CustomerId`, and `Surname` as they don’t contribute to prediction.
- **Checked Missing Values:** No missing values were found in the dataset.
- **Encoded Categorical Variables:** Converted `Gender` and `Geography` using label encoding and one-hot encoding.
- **Feature Importance Analysis:** Identified key features contributing to churn using Random Forest.

## 📊 Models Implemented
We trained multiple machine learning models and evaluated their performance:

### 1️⃣ Logistic Regression
- **Accuracy:** 82%
- **Classification Report:** Precision, Recall, and F1-score included.

### 2️⃣ Decision Tree
- **Accuracy:** 84%
- **Classification Report:** Precision, Recall, and F1-score included.

### 3️⃣ Random Forest
- **Accuracy:** 87%
- **Classification Report:** Precision, Recall, and F1-score included.

### 4️⃣ XGBoost
- **Accuracy:** 86%
- **Classification Report:** Precision, Recall, and F1-score included.

## 🔑 Key Insights
- **Age** and **Number of Products** were the most significant factors influencing churn.
- Customers from **Germany** had a higher likelihood of churning.
- **Active members** were less likely to leave.
- **XGBoost and Random Forest** provided the highest accuracy.

## 🚀 Next Steps
- **Hyperparameter tuning** to improve model performance.
- **Handling class imbalance** using SMOTE or weighted models.
- **Explainable AI (SHAP)** to interpret individual predictions.

## 🛠️ Tech Stack
- **Python** (pandas, numpy, sklearn, xgboost, matplotlib, seaborn)
- **Jupyter Notebook** for experimentation
  
## 🏃 Steps to Run the Project

1️⃣ Clone the Repository:

git clone [https://github.com/Roshni-seth/Customer-Churn-Pridiction/Model.git](https://github.com/Roshni-seth/Customer-Churn-Prediction/tree/main)
cd churn-prediction

2️⃣ Install Dependencies:

pip install -r requirements.txt

3️⃣ Download Dataset:

Ensure Churn_Modelling.csv is in the working directory.

4️⃣ Run the Jupyter Notebook:

jupyter notebook

Open Model.ipynb and run the cells sequentially.

5️⃣ Analyze Results:

The trained models and feature importance analysis will be displayed in the notebook.

