# 🚢 Titanic - Machine Learning from Disaster

Welcome to my first independent Data Science project on Kaggle!

This project marks the beginning of my personal data science journey after working on multiple data-driven projects. Here, I aim to apply and showcase my skills in data preprocessing, exploration, visualization, and machine learning modeling on the classic Titanic dataset.

---

## 📘 Project Overview

The sinking of the Titanic is one of the most infamous shipwrecks in history. In this Kaggle competition, the challenge is to build a predictive model that answers the question: **“What sorts of people were more likely to survive?”** using passenger data such as age, gender, class, etc.

---

## 🧠 Objectives

- Apply practical data science skills learned.
- Explore and clean real-world data.
- Engineer relevant features to improve model performance.
- Evaluate various classification models.
- Interpret results and extract key insights.

---

## 📂 Repository Structure


---

## 🔍 Exploratory Data Analysis (EDA)

- Checked missing values, outliers, and overall distribution of features.
- Visualized survival rates based on key variables such as **Sex**, **Pclass**, **Embarked**, and **Age**.
- Observed patterns in **family size**, **ticket class**, and **fare amount**.

---

## 🧹 Data Preprocessing & Feature Engineering

- Imputed missing values for `Age`, `Embarked`, and `Fare`.
- Converted categorical variables using label encoding and one-hot encoding.
- Created new features like:
  - `FamilySize` = `SibSp` + `Parch` + 1
  - `IsAlone` = 1 if `FamilySize` == 1 else 0
  - `Title` extracted from `Name`

---

## 🤖 Models Used

- Logistic Regression (Baseline)
- Decision Tree Classifier
- Random Forest
- Support Vector Machine

Model performance was evaluated using:
- Accuracy Score
- Confusion Matrix
- Cross-Validation

---

## 📈 Results

- **Final Model**: Random Forest Classifier
- **Public Kaggle Score**: *Pending...*
- **Top Predictive Features**: `Sex`, `Pclass`, `Fare`, `Title`, `IsAlone`

---

## ✅ Tools & Technologies

- Python
- Jupyter Notebooks
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## 📌 Lessons Learned

- The importance of feature engineering in improving model accuracy.
- Handling missing values with context-aware techniques.
- Comparing multiple classification models to find the best fit.
- Understanding the trade-off between model simplicity and performance.

---

## 🚀 Future Improvements

- Add hyperparameter tuning (e.g., using `GridSearchCV`)
- Try more advanced models (e.g., XGBoost, LightGBM)
- Build a web dashboard for predictions using Streamlit or Flask
- Perform more in-depth feature selection and importance analysis

---

## 👩🏽‍💻 About Me

I'm a passionate data science learner currently studying at **WorldQuant University**. I've completed multiple hands-on projects in data science and am eager to apply my skills to real-world problems. This Titanic project is the first step toward building a robust portfolio in AI and Data Science.

- 🔗 [LinkedIn](https://www.linkedin.com/in/ashley-mekolle-66136b256/)
- 🌐 Portfolio: Coming soon

---

## 📬 Contact

**Ashley Mekolle**  
📧 mekolleashleyam@gmail.com 

---

> “The journey of a thousand models begins with a single dataset.”
