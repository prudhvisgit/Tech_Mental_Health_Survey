# 🧠 Mental Health in Tech Industry — Exploratory Data Analysis

## 📌 Overview

This project focuses on performing Exploratory Data Analysis (EDA) on a mental health survey dataset conducted among employees in the tech industry. The aim is to understand the factors affecting mental health in the workplace and how treatment-seeking behavior varies with age, gender, family history, job type, and more. The insights drawn will help employers, HR departments, and mental health advocates to build better workplace wellness strategies.

---

## 🎯 Business Objective

The objective of this analysis is to understand how the frequency of mental health issues and attitudes towards treatment vary by geographic and demographic factors. It also seeks to uncover the strongest predictors of mental health challenges in a workplace, helping organizations design supportive environments for their employees.

---

## 🧾 Dataset Information

* **Source**: OSMI Mental Health in Tech Survey
* **Total Rows**: \~1250
* **Total Columns**: 27
* **Features Include**:

  * `Age`, `Gender`, `Country`, `self_employed`, `family_history`, `treatment`, `remote_work`, `tech_company`, `work_interfere`, etc.

---

## 🧹 Data Cleaning & Wrangling

* Normalized inconsistent gender labels (e.g., “M”, “male”, “Male” → “Male”).
* Removed outlier age values (e.g., ages < 18 or > 75).
* Filled or dropped missing values depending on context.
* Encoded categorical variables for correlation and pair plot analysis.
* Removed uninformative columns like `comments`.

---

## 📊 Exploratory Data Analysis (EDA)

### ✅ Univariate Analysis

* **Age Distribution**: Most respondents are between 25 and 35 years.
* **Gender Distribution**: Majority are male, followed by female, others, and transgender.
* **Treatment Count**: Shows how many have sought mental health treatment.

### ✅ Bivariate Analysis

* **Age vs Treatment (Boxplot)**: No strong variation; age is not a major predictor.
* **Treatment by Gender (Bar Chart)**: Females are more likely to seek treatment than males.
* **Family History vs Treatment**: Strong link between family history and treatment-seeking.

### ✅ Correlation Heatmap

Shows moderate correlation between treatment and family history. Age and self-employment show low correlation.

### ✅ Pair Plot

Detailed view of interaction between numerical and encoded categorical features, grouped by treatment status.

---

## 📍 Key Insights

* Employees with **family history** of mental illness are significantly more likely to seek treatment.
* **Gender** plays a role: females seek treatment more than males.
* Working in a **tech company** or being **self-employed** may affect mental health tendencies.
* **Remote work** does not strongly influence treatment-seeking behavior.
* **Age** is not a strong predictor of treatment.

---

## 💼 Business Impact

These insights can help HR departments and organizations:

* Create **inclusive mental health policies**.
* Focus on **early intervention** for employees with known risk factors.
* Promote **awareness and openness** about mental health in tech.
* **Encourage treatment** through supportive workplace programs.

---

## 📂 Project Structure

```bash
📁 mental-health-eda/
│
├── 📊 charts/                      # Visualizations
├── 📁 data/
│   └── survey.csv                 # Cleaned dataset
├── 📜 EDA_Mental_Health.ipynb     # Jupyter Notebook
├── 📄 README.md                   # Project Summary
└── 📌 insights.txt                # Summary of findings
```

---

## 🚀 Future Work

* Use predictive models to classify who is likely to seek treatment.
* Deep-dive by country or company size for more localized policies.
* Build an interactive dashboard using Power BI or Streamlit.

---

## 🧠 Conclusion

This EDA sheds light on workplace mental health and factors influencing treatment. The findings can drive positive change in organizational culture, promote mental well-being, and improve employee satisfaction and productivity.


