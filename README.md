# 🚢 Predicting Titanic Survival with Machine Learning: A Historical Data Case Study

Applying machine learning to history — predicting passenger survival on the Titanic using Logistic Regression and real-world classification techniques.

---

## 📌 Project Overview

This project explores the **Titanic dataset** to build a classification model that predicts passenger survival based on attributes like age, class, gender, and embarkation port. It serves as a practical and historical example of how **supervised learning** and **logistic regression** can be applied to real-world scenarios.

The case study blends **data preprocessing**, **feature engineering**, **modeling**, and **evaluation** to provide insights while strengthening core machine learning concepts.

---

## 🎯 Objectives

- Clean and prepare data for classification
- Engineer relevant features from categorical and numerical columns
- Train and evaluate a Logistic Regression model
- Create a user interface for survival prediction
- Interpret results using classification metrics

---

## 🗂️ Dataset

The dataset includes information for over 800 Titanic passengers:

- 👤 Passenger Details: Age, Sex, Class, Fare, Embarkation  
- 🛳️ Travel Information: Pclass, Ticket, Cabin (mostly null)  
- 🎯 Target Variable: `Survived` (0 = No, 1 = Yes)  

---

## 🔍 Key Highlights of the Analysis

### ✅ Data Cleaning & Preprocessing

- Dropped irrelevant columns: `PassengerId`, `Name`, `Ticket`
- Filled missing values:
  - `Age`: median imputation
  - `Embarked`: mode imputation
- Removed `Cabin` column due to excessive nulls

### 🛠️ Feature Engineering & Encoding

- Converted categorical columns:
  - `Sex`, `Embarked` → One-Hot Encoding
- Standardized input structure for modeling

### 🤖 Model Building with Logistic Regression

- Used `LogisticRegression` from Scikit-learn
- Split dataset using `train_test_split` (80/20 ratio)
- Trained on selected features to predict survival

### 📈 Model Evaluation

- Evaluated with:
  - Accuracy
  - Precision
  - Recall
  - F1-Score
- Used a **classification report** to assess model on both train and test sets

### 🧠 User Prediction Interface

- Implemented an interactive section:
  - Users input hypothetical passenger data
  - Model predicts survival likelihood based on inputs
    
---

## 🛠 Tools & Technologies Used

- **Python**
  - `pandas`, `numpy` – data handling
  - `matplotlib`, `seaborn` – visualization
  - `scikit-learn` – modeling and evaluation
- **Jupyter Notebook** – for code experimentation and narrative analysis

---

## 💡 Conclusion

This project illustrates how **logistic regression** can be used to derive insights from historical data. By preparing, visualizing, and modeling the Titanic dataset, we gain a deeper understanding of:
- Feature impact on survival
- Classification modeling techniques
- Data-driven storytelling through real events

A great foundational classification project for data science learners and machine learning enthusiasts.

---

## 🔮 Future Enhancements

- Implement cross-validation and hyperparameter tuning  
- Compare performance with other classifiers (Random Forest, SVM, KNN)  
- Build a web interface using Streamlit or Flask  
