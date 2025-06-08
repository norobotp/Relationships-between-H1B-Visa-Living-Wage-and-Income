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

---

# 🧾 H1B 비자 및 생활임금 분석

이 프로젝트는 H1B 비자 승인과 해당 직종의 **생활임금(living wage)** 또는 **제시 임금(offered wage)** 간의 관계를 **데이터 기반 분석**을 통해 조사한 결과입니다. 프로젝트는 세 부분으로 구성되어 있습니다: **탐색적 데이터 분석(EDA)**, **통계 분석**, **머신러닝 기반 예측 모델링**.

---

## 🔍 개요
본 프로젝트의 주요 목표는 다음과 같습니다:

- 산업, 기업, 지역별로 H1B 비자 승인률의 추세와 격차를 시각화
- 임금 수준과 기타 요소들이 비자 승인에 어떤 영향을 미치는지에 대한 통계적 가설 검정
- 머신러닝 모델을 통해 승인 확률을 예측하고, 중요 요인을 식별

---

## 📊 1부: 탐색적 데이터 분석 (EDA)

- H1B 신청 데이터 전처리 및 정제
- 산업, 주(state), 임금 수준, 직무 유형에 따른 승인률 분석
- 지역 및 직업별 **제시 임금**과 **생활임금**의 격차를 시각화

---

## 📈 2부: 통계 분석

- **로지스틱 회귀 분석**을 통해 승인 여부(이진 변수)를 모델링
- 주요 변수(임금 격차, 직무, 고용주 등)에 대한 통계적 추론 수행
- 변수별 **오즈비(odds ratio)** 및 **신뢰구간** 해석
- 다양한 요인 수준에서의 베이스라인 승인률 비교

---

## 🤖 3부: 머신러닝 예측 모델링

- 사용한 모델:
  - **랜덤 포레스트**
  - **XGBoost**
  - **로지스틱 회귀** (벤치마크용)
- **교차 검증** 및 **변수 중요도(feature importance)** 분석 수행
- 임금 격차 및 지역 기반 특성의 예측력 평가

---

## ⚙️ 사용 기술

- `Python`, `pandas`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`, `statsmodels`
- 로지스틱 회귀, 트리 기반 모델, 변수 중요도 분석
- Jupyter Notebook → HTML 리포트로 결과 내보내기

---

## 📁 결과

- 다음과 같은 3개의 상세 HTML 분석 리포트:
  - **EDA 리포트**
  - **통계 분석 리포트**
  - **머신러닝 리포트**

---

## 💡 프로젝트 동기

H1B 비자는 미국 기술 및 노동 생태계에서 핵심적인 역할을 합니다. 본 프로젝트는 **임금 경쟁력**이 비자 승인에 어떤 영향을 미치는지를 분석함으로써, **공정한 고용 관행**과 **이민 정책 개선**에 기여하고자 했습니다.

---

> ※ 이 프로젝트는 **미시간대학교(University of Michigan)** 데이터 사이언스 대학원 수업의 일환으로 수행되었습니다.

