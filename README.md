# 🚗 UK Traffic Accidents — Analysis & Predictive Model

**By Abdel Rahman Khwaira**  
B.Sc. Mathematics · Data Science & AI Trainee at SHAI · Data Analysis Fellow at Correlation One

---

## 📌 Overview

This project analyzes **144,000+ UK road accident records from 2022** to identify patterns and build a classification model that predicts accident severity across 3 classes: **Slight, Serious, and Fatal**.

---

## 🎯 Objectives

- Clean and prepare a real-world messy dataset
- Perform exploratory data analysis to find root causes and patterns
- Build and compare multiple ML classification models
- Document model bias issues and improvement opportunities

---

## 📁 Project Structure

```
├── UK_Traffic_Accidents.ipynb   # Main notebook (cleaning + EDA + models)
├── README.md
```

> **Dataset:** [UK Road Accidents 2022 — Kaggle](https://www.kaggle.com/datasets/abdulmannan/road-accidents-cav/data)  
> Download `accidents.xlsx` from Kaggle and place it in the same folder before running.

---

## 🛠️ Tools & Libraries

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=flat&logo=python&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat&logo=python&logoColor=white)

---

## 📊 Models Tested

| Model | Notes |
|-------|-------|
| Decision Tree (baseline) | Fast, interpretable |
| Decision Tree (tuned) | GridSearchCV hyperparameter tuning — **Best: 86% accuracy** |
| K-Nearest Neighbors | Required feature scaling |
| Random Forest | Ensemble of 100 trees |
| AdaBoost | Sequential boosting with shallow trees |

---

## ✅ Key Results

- **Best model:** Decision Tree (tuned) — **86% accuracy**
- Identified class imbalance bias (majority "Slight" accidents inflate accuracy)
- Documented improvement roadmap including SMOTE and OrdinalEncoder

---

## ⚠️ Known Bias & Limitations

- Dataset is heavily imbalanced — "Slight" accidents dominate
- Model underperforms on "Fatal" class due to very few samples
- LabelEncoder may introduce unintended ordering on ordinal features

---

## 📎 Related Links

- 📊 [Datafolio (EDA Presentation)](https://docs.google.com/presentation/d/1Mog2uuKtRYJYqC3H7imj1tcgcgCYsIg6/edit)
- 💼 [LinkedIn](https://www.linkedin.com/in/abdel-rahman-khwaira)
- 🌐 [Portfolio](https://abdel-rahman-khwaira.github.io)
