# 🇨🇦 Canada Per Capita Income Prediction using Linear Regression

## 📌 Project Overview
This project uses **Simple Linear Regression** to analyze and predict **Canada’s per capita income** based on historical data from **1970 to 2016**.

The objective is to:
- Understand the relationship between **year** and **per capita income**
- Train a regression model
- Evaluate model performance
- Predict future income values

---

## 📊 Dataset Description
- **Dataset:** Canada Per Capita Income
- **Records:** 47 years (1970–2016)
- **Features:**
  - `year` – Independent variable
  - `per capita income (US$)` – Target variable

---

## 🛠️ Tools & Libraries Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📈 Exploratory Data Analysis
- Visualized income trends over years using scatter plots
- Observed a **strong upward trend** with minor economic fluctuations
- Clear linear relationship between year and income

---

## 🤖 Model Building
- **Algorithm:** Simple Linear Regression
- **Train-Test Split:**  
  - 70% Training  
  - 30% Testing
- **Model:** `sklearn.linear_model.LinearRegression`

---

## 📊 Model Performance
- **R² Score:** **0.75**

This means:
- The model explains **~75% of the variance** in per capita income using the year alone.

---

## 🔮 Predictions

### Future Income Prediction
```python
reg.predict([[2020], [2021]])

Predicted Results:

2020: $42,511

2021: $43,359
