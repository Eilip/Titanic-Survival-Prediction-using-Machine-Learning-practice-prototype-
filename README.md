# 🚢 Titanic Survival Prediction using Machine Learning

## 📌 Project Overview
This project applies Machine Learning techniques to predict whether a passenger survived the Titanic disaster. The dataset comes from the famous Kaggle Titanic competition.

The goal is to build a predictive model using data preprocessing, feature engineering, and classification algorithms.

---

## 📊 Dataset Information
The dataset includes the following features:

- PassengerId
- Pclass (Ticket class)
- Name
- Sex
- Age
- SibSp (Siblings/Spouses aboard)
- Parch (Parents/Children aboard)
- Ticket
- Fare
- Cabin
- Embarked
- Survived (Target Variable)

---

## ⚙️ Project Workflow

### 1️⃣ Data Preprocessing
- Handling missing values
- Encoding categorical variables
- Feature selection
- Data normalization (if required)

### 2️⃣ Exploratory Data Analysis (EDA)
- Survival rate by gender
- Survival rate by class
- Age distribution
- Correlation heatmaps

### 3️⃣ Model Building
Machine Learning models used:
- Logistic Regression
- Decision Tree
- Random Forest
- (Optional) Support Vector Machine

### 4️⃣ Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report
- Cross Validation

---

## 🧠 Model Prediction Example

Input:
- Sex: Female
- Pclass: 1
- Age: 25
- Fare: 100

Output:
- Prediction: Survived ✅

---

## 📈 Results
The best performing model achieved an accuracy of:

**Accuracy: ~80-85% (depending on tuning)**

(Random Forest typically performs best for this dataset.)

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🚀 How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/yourusername/titanic-ml-prediction.git
