# 🧾 H1B Visa and Living Wage Analysis

This project investigates the relationship between H1B visa approval and prevailing/living wage requirements using data-driven analysis. It is divided into three parts: Exploratory Data Analysis (EDA), Statistical Modeling, and Machine Learning.

## 🔍 Overview
Our main objectives were to:
- Explore trends and disparities in H1B visa approvals across occupations, companies, and locations
- Test hypotheses about the role of wage level and other factors in visa outcomes
- Predict approval likelihood using machine learning models

## 📊 Part 1: Exploratory Data Analysis (EDA)
- Cleaned and preprocessed H1B application data
- Analyzed approval rates across industries, states, wage levels, and job types
- Visualized disparities between **offered wage** and **living wage** by region and occupation

## 📈 Part 2: Statistical Analysis
- Performed logistic regression to model the binary approval outcome
- Conducted inference on key predictors (wage difference, job title, employer)
- Interpreted the odds ratio and confidence intervals of each variable
- Compared baseline approval trends across different covariate levels

## 🤖 Part 3: Machine Learning Modeling
- Implemented models including:
  - Random Forest
  - XGBoost
  - Logistic Regression (for benchmarking)
- Used cross-validation and feature importance to evaluate model performance
- Assessed predictive power of wage difference and location-based features

## ⚙️ Technologies Used
- `Python`, `pandas`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`, `statsmodels`
- Logistic regression, tree-based models, feature importance analysis
- Jupyter Notebook → Exported as HTML reports

## 📁 Output
- Three detailed HTML reports:
  - **EDA Report**
  - **Statistical Analysis Report**
  - **Machine Learning Report**

---

## 💡 Motivation
H1B visas are a key part of the U.S. tech and labor ecosystem. Understanding how wage competitiveness affects approval outcomes can inform fairer labor practices and better immigration policy insights.

---

*Note: This project was conducted as part of a graduate-level data science course at the University of Michigan.*
