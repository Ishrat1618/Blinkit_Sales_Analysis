# 🛒 Blinkit Grocery Sales Analysis & Demand Prediction

## 📌 Executive Summary
This project analyzes grocery sales data inspired by Blinkit using SQL, Python, and Machine Learning.  
The goal is to identify key sales drivers and predict next-month demand to support inventory planning, pricing decisions, and outlet performance optimization.

---

## 🧩 Business Problem
Quick-commerce platforms like Blinkit face challenges such as:
- Stock-outs and overstocking
- Inventory wastage
- Uneven outlet performance
- Difficulty in forecasting demand

This project addresses these challenges using data-driven analysis and predictive modeling.

---

## 🛠️ Tools & Technologies
- **SQL (MySQL)** – Data storage and business queries  
- **Python** – Data analysis and modeling  
- **Pandas & NumPy** – Data manipulation  
- **Matplotlib & Seaborn** – Data visualization  
- **Scikit-learn** – Machine learning (Linear Regression)

---

## 📂 Dataset Overview
The dataset contains:
- Product attributes (type, price, visibility, fat content)
- Outlet details (type, size, location, establishment year)
- Sales values (`Item_Outlet_Sales`)

The data represents retail store performance used for analytical purposes.

---

## 🔍 Exploratory Data Analysis (EDA)
Key analyses include:
- Sales distribution by item category
- Outlet type performance comparison
- Average sales trend across outlet age groups

These insights help identify high-performing products and store formats.

---

## 🧮 SQL-Based Business Insights
SQL queries were used to:
- Analyze total sales by item type
- Compare outlet performance
- Evaluate location-based sales trends

Screenshots of SQL queries and results are included in the notebook.

---

## 🧠 Feature Engineering
- **Outlet_Age** was derived from establishment year
- **Monthly_Sales** was estimated from total sales for demand prediction
- Categorical variables were encoded and numerical features standardized

---

## 🤖 Machine Learning Model
- **Model Used:** Linear Regression  
- **Objective:** Predict next-month sales  
- **Evaluation Metrics:** MAE, R² Score  

The model captures relationships between pricing, outlet characteristics, and sales performance.

---

## 📊 Feature Importance
Feature importance analysis shows that:
- Item price
- Outlet type
- Outlet age  
are among the most influential predictors of sales.

(Data leakage was carefully handled by excluding target-derived features.)

---

## 🔄 Scenario Analysis
A pricing scenario simulation was performed to analyze the impact of a **10% price increase** on predicted monthly sales.

This helps understand pricing sensitivity and supports business decision-making.

---

## 📈 Business Recommendations
- Prioritize inventory for high-demand item categories
- Focus expansion on high-performing outlet types
- Use demand prediction to reduce wastage and stock-outs
- Monitor pricing impact on sales volume

---

## ⚠️ Limitations & Future Work
- Dataset does not capture seasonality
- Real-time demand data is not available
- Future work can include time-series forecasting and advanced ML models

---

## ✅ Conclusion
This project demonstrates an end-to-end analytics and machine learning workflow, transforming raw sales data into actionable business insights suitable for real-world applications.
