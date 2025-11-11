# ML Sprint — Titanic

This project includes:
- Exploratory Data Analysis (EDA)
- Data Preprocessing & Feature Engineering
- Model Building (Logistic Regression, Decision Tree, Random Forest)
- Model Evaluation & Comparison

## How to Run
1. Clone the repo:
2. Open any notebook under `/notebooks/`
3. Dataset: Download `train.csv` from Kaggle Titanic dataset and place it inside `data/` folder.

---

# 🧠 Titanic Survival Prediction — Machine Learning Project

### 📘 Overview
This project predicts whether a passenger survived the Titanic disaster using machine learning models such as Logistic Regression, Decision Tree, and Random Forest.

### 📊 Dataset
Dataset used: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)

### 🚀 Steps
1. **EDA (Exploratory Data Analysis):**
   - Visualized distributions (Age, Fare, Sex, Pclass)
   - Found key patterns (Females, higher Fare, 1st Class → more survival)

2. **Feature Engineering:**
   - Filled missing values (Age, Embarked)
   - Created new features (FamilySize, IsAlone, Title, AgeBand)
   - Encoded categorical data using Label Encoding and OneHotEncoding

3. **Modeling:**
   - Tested Logistic Regression, Decision Tree, Random Forest
   - Tuned Random Forest using GridSearchCV → 85% Accuracy
   - Used ROC–AUC, Confusion Matrix, and Feature Importance for evaluation

4. **Explainability:**
   - Used PDP, ICE plots to understand model behavior
   - Key features: Sex, Fare, Pclass, Age

5. **Final Pipeline:**
   - Combined preprocessing + model into one pipeline
   - Saved final model (`models/final_titanic_pipeline.joblib`)

### 🏁 Results
- **Best Model:** Random Forest (Tuned)
- **Accuracy:** ~0.85 on test data
- **Top Features:** Sex, Fare, Pclass, Age

### 🧰 Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

### 💡 Author
**Gurpreet Singh** — Data Science & Machine Learning Enthusiast
