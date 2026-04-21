# 🧠 Mental Health in Tech Workers  
### Data Analysis & Machine Learning Project

---

## 📌 Project Overview

This project analyzes mental health, burnout, and work-life balance in tech workers using real-world survey data.  

The goal is to understand how workplace conditions and personal factors influence mental health treatment-seeking behavior and to build a simple predictive model.

---

## 🎯 Problem Statement

Tech workers often face high workloads, stress, and burnout, yet mental health issues are often underreported.

This project aims to explore:

- What factors influence mental health treatment-seeking behavior?
- How do workplace conditions affect mental health?
- Can we predict whether a person will seek treatment?

---

## 📊 Dataset

The dataset contains survey responses from tech workers, including:

- Demographics (Age, Gender, Country)
- Workplace conditions (Benefits, Care options, Remote work, etc.)
- Mental health indicators (Work interference, Treatment history)
- Workplace culture and support systems

---

## 🧹 Data Cleaning

Key steps performed:

- Removed irrelevant columns (`state`, `comments`)
- Handled missing values in categorical variables
- Standardized inconsistent gender values
- Removed unrealistic age values
- Encoded categorical features for modeling

---

## 📊 Exploratory Data Analysis (EDA)

### 👤 Demographics
- Dataset is male-dominated, reflecting gender imbalance in tech.
- Most respondents fall within working-age groups.

### 🧠 Mental Health Insights
- Individuals with family history of mental health issues are more likely to seek treatment.
- Higher work interference strongly correlates with treatment-seeking behavior.

### 🏢 Workplace Factors
- Employees with benefits, care options, and wellness programs are more likely to seek treatment.
- Workplace support plays a key role in reducing barriers to mental health care.

---

## 🤖 Machine Learning Model

A Logistic Regression model was used to predict treatment-seeking behavior.

### 🔹 Target Variable:
- `treatment` (Yes = 1, No = 0)

### 🔹 Features:
- Work interference
- Family history
- Workplace benefits
- Care options
- Wellness programs
- Remote work status
- Workplace culture factors

---

## 📈 Model Performance

- **Accuracy:** 84%
- Balanced precision and recall across both classes

### Key Observation:
The model performs slightly better at identifying individuals who seek treatment.

---

## 🔍 Key Insights

- Work interference is the strongest predictor of mental health treatment.
- Workplace support systems significantly increase treatment-seeking behavior.
- Family history increases awareness and likelihood of seeking help.
- Mental health outcomes are influenced by both personal and workplace factors.

---

## 💡 Conclusion

This project demonstrates that mental health in tech workers is shaped by both workplace environment and personal background.

A clear pattern was observed:
> Higher work interference and stronger workplace support increase the likelihood of seeking mental health treatment.

---

## 🛠️ Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---



