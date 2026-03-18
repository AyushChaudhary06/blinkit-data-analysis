# 🛒 Blinkit Sales Data Analysis & Prediction Report

---

## 📌 1. Project Overview

This project presents an end-to-end data analysis and machine learning solution for Blinkit’s grocery sales dataset. The objective is to analyze historical sales data, uncover business insights, and build a predictive model to forecast future sales.

The project integrates **Python-based data analysis, visualization, and machine learning** along with **interactive dashboards** to provide a complete analytical solution.

---

## 🎯 2. Objectives

* Analyze sales performance across products and outlets
* Identify key factors influencing sales
* Understand customer and location-based trends
* Build a machine learning model to predict sales
* Visualize insights using charts and dashboards

---

## 📂 3. Dataset Description

The dataset contains structured information about:

* Item details (type, fat content, visibility, weight)
* Outlet details (type, size, location, establishment year)
* Sales data (target variable)

### Key Columns:

* `Item_Identifier`
* `Item_Type`
* `Outlet_Identifier`
* `Outlet_Location_Type`
* `Sales`

---

## 🧹 4. Data Preprocessing

The dataset was cleaned and prepared using Python:

* Handled missing values:

  * Item Weight → filled with mean
  * Outlet Size → filled with mode

* Standardized column names for consistency

* Converted categorical variables using **One-Hot Encoding**

* Separated features and target variable for model training

---

## 🔍 5. Exploratory Data Analysis (EDA)

EDA was performed using **Python (Pandas & Matplotlib)** to understand patterns and relationships in the dataset.

### Visualization Techniques Used:

* 📊 Bar charts to analyze sales across item types
* 📈 Histograms to study sales distribution
* 🥧 Pie charts to understand category contribution
* 📦 Box plots to detect outliers
* 📉 Line charts for outlet trends over years

### Key Findings:

* 🥗 Low Fat items generate higher sales
* 🏪 Supermarket Type1 outlets perform best
* 📍 Tier 2 and Tier 3 cities contribute significantly to revenue
* 📦 A few product categories dominate total sales

Additionally, an automated EDA report was generated using Sweetviz for deeper insights.

<p align="center">
<img src="Report/sweetviz/figures/02overview.png" width="700">
</p>
---

## 🤖 6. Machine Learning Model

### Model Used:

* Random Forest Regressor

### Steps:

1. Data preprocessing and encoding
2. Train-test split (80/20)
3. Model training using Random Forest
4. Prediction on test data

### Evaluation Metrics:

* Mean Absolute Error (MAE)
* R² Score

The model demonstrated good performance in predicting sales values.

---

## 📊 7. Prediction Output

A prediction file was generated:

`prediction_output.csv`

### Contains:

* Item Identifier
* Outlet Identifier
* Actual Sales
* Predicted Sales

This file is used for visualization and performance evaluation.

---

## 📈 8. Dashboards

### 🔹 Business Analysis Dashboard

Built using Tableau to visualize:

* Sales distribution across categories
* Outlet performance
* Location-based insights
* Customer purchase trends

<p align="center">
<img src="dashboards/screenshots/blinkit_analysis_screenshots/Tableau Dashboard.png" width="700">
</p>
---

### 🔹 Sales Prediction Dashboard 🤖

Focused on machine learning insights:

* Actual vs Predicted Sales comparison (Scatter Plot)
* Error analysis
* Top performing items
* Interactive filters for better exploration

<p align="center">
<img src="dashboards/screenshots/sales_prediction_screenshots/overview dashboard.png" width="700">
</p>
---

## 🧠 9. Key Insights

* Low Fat products consistently outperform Regular products
* Supermarket Type outlets generate the highest revenue
* Tier 2 & Tier 3 cities show strong sales potential
* The machine learning model effectively predicts sales trends

---

## 🚀 10. Business Impact

* Enables identification of high-performing products
* Supports inventory and demand planning
* Improves decision-making using predictive insights
* Helps businesses optimize sales strategies

---

## 🛠️ 11. Tools & Technologies

* Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
* SQL
* Tableau
* Sweetviz
* Excel

---

## ⚠️ 12. Limitations

* Model performance depends on data quality
* Limited feature engineering
* External factors like promotions and seasonality not included

---

## 🔮 13. Future Improvements

* Hyperparameter tuning for better model performance
* Advanced feature engineering
* Deployment using Streamlit for real-time predictions
* Integration with live business data

---

## 🏆 14. Conclusion

This project demonstrates a complete data science workflow, starting from raw data processing to advanced analytics and machine learning. By combining descriptive and predictive approaches, it provides a comprehensive solution for business insights and forecasting.

---

## 👑 Author

**Ayush Chaudhary**
Aspiring Data Analyst | Machine Learning Enthusiast

---
