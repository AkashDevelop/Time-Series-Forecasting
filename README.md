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
- **datas:** `sales_data`, `ingredients_data`
  
### 🧹 Data Cleaning
- Handled missing values in columns such as `pizza_name_id`, `pizza_category`, `pizza_ingredients`, etc.
- Used appropriate imputation and removal strategies for clean data processing.

---

## 🔬 Exploratory Data Analysis (EDA)

### 📉 Key Insights
- Identified **seasonal** and **weekly** sales patterns.
- Visualized sales trends to highlight high-demand and low-demand periods.

---

## 📅 Forecast for Next 7 Days

| Date       | Forecasted Sales (Units) |
|------------|-------------------------|
| 2016-01-01 | 797.68                  |
| 2016-01-02 | 753.62                  |
| 2016-01-03 | 763.14                  |

---

## 🛠 Feature Engineering

### ✨ Features Used
- Extracted features like **day of the week**, **month**, and **previous day’s sales**.
- Modeled **seasonality** and **trend** for better prediction.

## ⚙️ Model Overview

### Model Chosen:
- **ARIMA** for time series forecasting.

### Accuracy:
- Achieved a **MAPE of 16.83%** for forecast accuracy.

---

## 🍕 Ingredient Requirement Forecast

### 🌱 Ingredient Mapping
Calculated ingredient quantities based on forecasted sales.

#### Example Ingredients:

| Ingredient          | Quantity (grams) |
|----------------------|------------------|
| Pepperoni           | 347.09           |
| Mozzarella Cheese   | 259.55           |
| Mushrooms           | 364.32           |

---

## 📊 Visualizations

 **Ingredient Requirements Bar Plot**  
   ![Ingredient Bar Plot](https://github.com/user-attachments/assets/897b0002-b92b-44e8-8dcc-ba2476e6696b) 



✅ **Key Takeaways & Future Work**

### 🎯 Key Takeaways
- ARIMA was effective for forecasting ingredient requirements.  
- Achieved a MAPE value of **16.83%**, suitable for real-world use.  
  

---

### 🛠 Tech Stack
- **Programming Languages:** Python, SQL  
- **Libraries/Tools:** Pandas, NumPy, ARIMA, Matplotlib, Seaborn, Jupyter Notebook  

---

### 📝 Installation & Setup

**Clone this repository:**
```bash
git clone https://github.com/AkashDevelop/pizza-sales-forecasting.git


