# 🍕 Time Series Forecasting for Pizza Sales

**Capstone Project | Data Science | Machine Learning**  
_Optimizing Ingredient Requirements for Efficient Inventory Management_

![Pizza Sales Forecasting](https://github.com/user-attachments/assets/70b6fc4b-1fa5-4b72-a79c-e58aac5c3c16)


---

## 🚀 Project Overview

### 📊 Problem Statement
- Forecast daily pizza sales to predict ingredient requirements for inventory management.
- **Goal:** Accurately predict the required quantity of ingredients for the next 7 days based on historical sales data.

### 📝 Objectives
- Develop a forecasting model for pizza sales.
- Calculate ingredient quantities based on the forecasted sales.
- Optimize inventory stocking based on predicted demand.

---

## 🔍 Data Overview

### 🗂 Dataset
- **Period:** January 2015 to January 2016
- **Columns:** `order_date`, `daily_quantity`
  
### 🧹 Data Cleaning
- Handled missing values in columns such as `pizza_name_id`, `pizza_category`, `pizza_ingredients`, etc.
- Used appropriate imputation and removal strategies for clean data processing.

---

## 🔬 Exploratory Data Analysis (EDA)

### 📉 Key Insights
- Identified **seasonal** and **weekly** sales patterns.
- Visualized sales trends to highlight high-demand and low-demand periods.

#### 📊 Sales Distribution Example
```python
import matplotlib.pyplot as plt
df['daily_quantity'].plot(kind='line')
plt.title('Daily Pizza Sales')
plt.xlabel('Date')
plt.ylabel('Sales Quantity')
plt.show()

## 🛠 Feature Engineering

### ✨ Features Used
- Extracted features like **day of the week**, **month**, and **previous day’s sales**.
- Modeled **seasonality** and **trend** for better prediction.

```python
# Example: Lag Feature
df['previous_day_sales'] = df['daily_quantity'].shift(1)
