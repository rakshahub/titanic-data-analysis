# Titanic Survival Prediction — Data Science + ML Project

## Overview
This project analyzes the Titanic dataset and builds a machine learning model to predict whether a passenger would survive based on features like:
- Passenger class
- Gender
- Age
- Fare

The goal is to understand how data science + machine learning can derive insights from real-world historical data.

---

## 🛠 Tech Stack
| Area | Tools Used |
|------|------------|
| Language | Python |
| Libraries | Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn |
| Platform | Google Colab |
| Version Control | Git & GitHub |

---

## Exploratory Data Analysis (EDA)

### 🔹 Survival Rate by Gender
Women had a much higher survival rate than men.

![Survival by Sex](survival_by_sex.png)

### 🔹 Survival Rate by Passenger Class
Passengers in **1st class** had better survival chances.

![Survival by Class](survival_by_class.png)

---

## Machine Learning Model

**Algorithm used:** Logistic Regression  
**Model Accuracy:** `~80%`

| Model | Accuracy |
|--------|----------|
| Logistic Regression | ✅ ~0.80 |

---

## Prediction Example

**Input:**
```
Pclass = 3  
Sex = female  
Age = 22  
Fare = 7.25
```

**Output:**  
✅ Passenger would SURVIVE


## 📊 Visualizations

| Plot | Description |
|------|-------------|
| `survival_by_sex.png` | Females have higher survival chance than males |
| `survival_by_class.png` | Passengers in 1st class had higher survival rate |

---

## ✅ Technologies Used
| Category | Tools |
|----------|-------|
| Language | Python |
| Libraries | pandas, numpy, matplotlib, seaborn, scikit-learn |
| ML Model | Logistic Regression |
| IDE / Notebook | Jupyter Notebook / VS Code |

---

## 🎯 Results
| Metric | Value |
|--------|-------|
| Model Used | Logistic Regression |
| Accuracy | ~80% |

---

## ⭐ Conclusion
- Survival rate depends strongly on **gender and passenger class**
- Females and 1st class passengers were more likely to survive
- Machine learning model predicts survival effectively using basic features

---

## 👤 Author
**Rakshatha Prabhakaran — M.Tech CSE (Data Science | ML | Cloud)**
Project prepared for academic demonstration and portfolio usage.

---


