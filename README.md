#  **Time Series Forecasting for Pizza Sales**

**Capstone Project | Data Science | Machine Learning**  
_Optimizing Ingredient Requirements for Efficient Inventory Management_

![Pizza Sales Forecasting](https://github.com/user-attachments/assets/70b6fc4b-1fa5-4b72-a79c-e58aac5c3c16)

---

## 🚀 **Project Overview**

### 📊 **Problem Statement**
- **Goal:** Predict pizza sales and optimize ingredient requirements to improve inventory efficiency.
- Use **historical sales data** to forecast demand for the next 7 days.

### 🎯 **Key Objectives**
1. Develop an accurate **time series forecasting model**.
2. Map predicted sales to **ingredient quantities**.
3. Minimize waste and optimize **stock management**.

---

## 🔍 **Data Overview**

### 🗂 **Dataset Details**
- **Period:** January 2015 – January 2016  
- **Datasets:** `sales_data`, `ingredients_data`  

### 🧹 **Data Cleaning**
- Removed null values from `pizza_name_id`, `pizza_category`, and `pizza_ingredients`.
- Applied appropriate **imputation strategies** and data preprocessing.
- 
![Objective)](https://github.com/user-attachments/assets/f672ca02-35a4-4b34-a67e-6592a93ce34c)

---

## 🔬 **Exploratory Data Analysis (EDA)**

### 📉 **Key Insights**
- Sales exhibit **weekly** and **seasonal trends**.
- Visualizations revealed high-demand days (weekends) and low-demand days.

---

## ⚙️ **Model Overview**

### 📈 **Model Used**
- **ARIMA (AutoRegressive Integrated Moving Average)** for time series forecasting.

### 🎯 **Model Performance**
- Achieved **Mean Absolute Percentage Error (MAPE):** `16.83%`

---

## 📅 **7-Day Sales Forecast**

| Date       | Forecasted Sales (Units) |
|------------|-------------------------|
| 2016-01-01 | 797.68                  |
| 2016-01-02 | 753.62                  |
| 2016-01-03 | 763.14                  |
| 2016-01-04 | 790.31                  |
| 2016-01-05 | 808.55                  |
| 2016-01-06 | 789.91                  |
| 2016-01-07 | 770.48                  |

---

## 🍕 **Ingredient Requirement Forecast**

### 🌱 **Ingredient Mapping to Forecasted Sales**

Calculated **ingredient quantities** for predicted sales.

| Ingredient          | Quantity (grams) |
|----------------------|------------------|
| Pepperoni           | 347.09           |
| Mozzarella Cheese   | 259.55           |
| Mushrooms           | 364.32           |
| Dough               | 450.00           |
| Tomato Sauce        | 200.25           |

---

## 📊 **Visualizations**

### **1️⃣ Sales Trends**
- 📈 Time Series plot showcasing **daily sales trends**.
<img src="https://github.com/user-attachments/assets/ea9b9b01-afeb-47f1-8128-e875f5128fbd" alt="Sales Trends" width="60%">

### **2️⃣ Ingredient Bar Plot**
- **Ingredient Details**
<img src="https://github.com/user-attachments/assets/897b0002-b92b-44e8-8dcc-ba2476e6696b" alt="Ingredient Bar Plot" width="60%">

---

## ✅ **Key Takeaways**

- **ARIMA** proved effective for time series sales forecasting.  
- Achieved a **MAPE of 16.83%**, which is acceptable for real-world applications.  

---

## 🔮 **Future Work**
- Explore **SARIMA** to handle seasonal trends better.  
- Integrate **promotional and discount data** for enhanced forecast accuracy.  
- Incorporate **automated inventory alerts** to further optimize stock levels.

---

## 🛠 **Tech Stack**

| **Category**             | **Tools/Technologies**       |
|---------------------------|------------------------------|
| Programming Languages     | Python, SQL                 |
| Libraries                 | Pandas, NumPy, ARIMA        |
| Visualization             | Matplotlib, Seaborn         |
| IDE/Tools                 | Jupyter Notebook            |
| Data Storage              | SQLite                      |

---

## 📝 **Installation & Setup**

**Step 1:** Clone this repository:
```bash
git clone https://github.com/AkashDevelop/pizza-sales-forecasting.git
