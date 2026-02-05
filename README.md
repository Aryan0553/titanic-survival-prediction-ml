# 🚢 Titanic Survival Prediction – Machine Learning Pipeline
A complete end-to-end Machine Learning project that predicts passenger survival on the Titanic dataset using **Decision Tree Classifier** with proper data preprocessing, encoding, model training, evaluation, and serialization.

---


## 📌 Project Overview

This project demonstrates a **production-style ML workflow** including:
- Data cleaning & preprocessing
- Handling missing values
- One-Hot Encoding for categorical features
- Model training using Decision Tree
- Model evaluation
- Saving trained models for deployment

---


## 🧠 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Pickl

---

## 📂 Dataset

**Titanic Dataset**
- Target Variable: `Survived`
- Features Used:
  - Pclass
  - Sex
  - Age
  - SibSp
  - Parch
  - Fare
  - Embarked

Removed columns:
- PassengerId
- Name
- Ticket
- Cabin

---

## 🔄 Workflow

1. Load dataset
2. Drop irrelevant columns
3. Train-test split
4. Handle missing values using `SimpleImputer`
5. Encode categorical features using `OneHotEncoder`
6. Combine all transformed features
7. Train Decision Tree model
8. Evaluate model accuracy
9. Save trained model & encoders

---

## 📊 Model Performance

- **Algorithm:** Decision Tree Classifier
- **Accuracy:** ~77.6%

---

## 💾 Saved Models

All models are saved in the `models/` directory:

---

## 🚀 How to Run

```bash
pip install pandas numpy scikit-learn


