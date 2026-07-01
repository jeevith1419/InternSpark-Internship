# 🚀 Customer Churn Prediction using Machine Learning

## 📌 Project Overview

This project is developed as **Task 1** for the **Alfido Tech AI & Machine Learning Internship**. The objective is to build and evaluate a supervised machine learning model that predicts whether a customer is likely to churn based on demographic and service-related information.

The project demonstrates the complete machine learning pipeline, including data preprocessing, feature engineering, model training, evaluation, visualization, and model comparison.

---

## 🎯 Objective

* Build a supervised classification model for customer churn prediction.
* Compare multiple machine learning algorithms.
* Evaluate model performance using standard classification metrics.
* Understand the complete end-to-end machine learning workflow.

---

## 📂 Dataset

**Dataset:** Telco Customer Churn Dataset

**Source:** Kaggle

The dataset contains customer information such as:

* Customer demographics
* Account information
* Services subscribed
* Billing details
* Churn status (Target Variable)

---

## 🛠️ Technologies Used

* Python 3
* Google Colab
* NumPy
* Pandas
* Scikit-learn
* Matplotlib
* Seaborn
* Joblib

---

## ⚙️ Machine Learning Workflow

### 1. Data Preprocessing

* Removed unnecessary columns
* Converted data types
* Handled missing values
* One-Hot Encoding for categorical features
* Feature Scaling for numerical features

### 2. Train-Test Split

* 80% Training Data
* 20% Testing Data

### 3. Models Implemented

* Logistic Regression
* Random Forest Classifier

### 4. Cross Validation

* 5-Fold Cross Validation

### 5. Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix
* ROC Curve

---

## 📊 Project Structure

```text
Customer-Churn-Prediction/
│── Customer_Churn_Prediction.ipynb
│── WA_Fn-UseC_-Telco-Customer-Churn.csv
│── customer_churn_model.pkl
│── Task_1_Customer_Churn_Prediction_Final_Report.pdf
│── README.md
```

---

## 📈 Results

Both machine learning models performed well in predicting customer churn.

**Model Comparison**

* Logistic Regression

  * Strong baseline model
  * Fast and interpretable

* Random Forest

  * Higher predictive performance
  * Better ROC-AUC and F1-Score
  * Captures complex relationships between features

Random Forest was selected as the final model because it achieved the best overall performance.

---

## 📚 Learning Outcomes

* Applied data preprocessing techniques
* Built supervised classification models
* Compared multiple machine learning algorithms
* Evaluated models using industry-standard metrics
* Visualized model performance
* Saved the trained model for future deployment

---

## ✅ Internship Requirements Covered

* ✔ Data Preprocessing
* ✔ Feature Engineering
* ✔ Train-Test Split
* ✔ Cross Validation
* ✔ Logistic Regression
* ✔ Random Forest
* ✔ Accuracy
* ✔ Precision
* ✔ Recall
* ✔ F1-Score
* ✔ ROC-AUC
* ✔ Confusion Matrix
* ✔ ROC Curve
* ✔ Model Comparison
* ✔ Model Saving

---

## 🚀 Future Improvements

* Hyperparameter tuning using GridSearchCV
* XGBoost and LightGBM implementation
* Model deployment using Flask or FastAPI
* Explainable AI using SHAP
* Interactive dashboard with Streamlit

---

## 👨‍💻 Author

**JEEVITH HM**

AI & Machine Learning Intern
