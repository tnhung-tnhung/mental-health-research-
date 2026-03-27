# 🧠 Mental Health Analysis using XGBoost & SHAP

## 📌 Overview

This project explores the impact of COVID-19 lockdown on mental health using machine learning techniques.

We combine **XGBoost**, a powerful predictive model, with **SHAP (Explainable AI)** to not only predict outcomes but also understand the role of each influencing factor.

---

## 🎯 Objectives

* Analyze factors affecting mental health during social isolation
* Build predictive models for psychological outcomes
* Interpret model results using explainable AI

---

## 📊 Dataset

* Source: Survey data from Italy during COVID-19 lockdown
* Sample size: **1166 observations**
* Variables:

  * **Outcomes**: Depression, Unworthiness, Alienation, Helplessness
  * **Predictors**: Living conditions, demographics, social interaction, epidemiological indicators

---

## ⚙️ Methodology

* Model: **XGBoost Regression**
* Optimization: **Optuna (Bayesian Optimization)**
* Validation: **5-fold Cross Validation**
* Explanation: **SHAP analysis**

---

## 📈 Results

The model achieved stable predictive performance:

* MAE ranges from **0.8 to 1.0**
* Errors are relatively low on a 1–7 scale

---

## 🔍 Key Insights

* **Private living space** is a critical factor
* **Isolation duration** strongly impacts mental health
* Significant changes occur after **5–15 days of isolation**
* **Helplessness** shows the strongest increase

---

## 🛠️ Technologies

Python · XGBoost · SHAP · Optuna · Scikit-learn

---

## 👩‍💻 Authors

Le Thi Thuy Nhung et al.

---

## 📌 Notes

This project demonstrates how **Machine Learning + Explainable AI** can be applied in mental health research to generate both accurate and interpretable results.
