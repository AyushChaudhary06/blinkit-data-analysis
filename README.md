# 🛒 Blinkit Sales Data Analysis & Prediction

## 📌 Overview

An end-to-end data analysis and machine learning project on Blinkit’s grocery dataset using Python, SQL, and Tableau. The project uncovers key business insights and builds a predictive model to forecast sales, enabling both descriptive and predictive analytics.

---

## 🚀 Key Highlights

📊 Cleaned and processed raw data using Python
🔍 Performed exploratory data analysis (EDA)
🧮 Extracted insights using SQL queries
📈 Built interactive dashboards using Tableau
🤖 Developed a Machine Learning model (Random Forest) for sales prediction
📊 Created a prediction dashboard (Actual vs Predicted Sales)
📄 Generated automated EDA report using Sweetviz

---

## 📊 Dashboards
<p align="center">
  <img src="tableau/Screenshots/Tableau Dashboard.png" width="700">
</p>


### 1️⃣ Business Analysis Dashboard

* Sales distribution across item types
* Outlet performance analysis
* Location-based insights (Tier-wise sales)
* Customer purchase trends

### 2️⃣ Sales Prediction Dashboard 🤖

* Actual vs Predicted Sales comparison
* Error analysis (prediction accuracy)
* High vs low performing products
* Interactive filters for item & outlet

---

## 📈 Sample Insights

🥗 Low Fat products contribute higher sales
🏪 Supermarket Type outlets perform best
📍 Tier 2 & Tier 3 cities show strong sales trends
📦 Few item categories dominate revenue
🤖 ML model successfully predicts sales with strong accuracy

---

## 🧠 Machine Learning Pipeline

* Data Cleaning & Preprocessing
* Handling Missing Values
* Feature Encoding (One-Hot Encoding)
* Train-Test Split
* Model Training using Random Forest Regressor
* Model Evaluation (MAE, R² Score)
* Prediction Output Generation

---

## 📂 Project Structure

```
Blinkit-Data-Analysis/
│
├── data/
│   ├── raw/
│   ├── processed/
│   └── predictions/
│
├── python/
|   |──notebooks/
│   |       ├── analysis.ipynb
│   |       └── ml_model.ipynb
|   └── profiling.py
│   
├── dashboards/
│   |      ├── blinkit_analysis.twbx
│   |      └──sales_prediction.twbx
│   └──screenshots/
|
├── reports/
|   ├── Final_report.md
│   └── SweetViz_report.html
│
├── models/
│   └── random_forest_model.pkl
│
├── README.md
└── requirements.txt
```

---

## 📄 Detailed Analysis

👉 Full report available in **[View Detailed Report](Reports/Final_report.md)**
👉 Sweetviz EDA Report: `Reports/SweetViz_report.html`

---

## 🛠️ Tech Stack

* Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Sweetviz)
* SQL
* Tableau
* Excel

---

## ⚙️ How to Run

```bash
git clone <your-repo-link>
cd Blinkit-Data-Analysis
pip install -r requirements.txt
jupyter notebook
```

---

## 📊 Model Output

The model generates a prediction file:

* `prediction_output.csv`
* Contains Actual vs Predicted Sales
* Used for building the ML dashboard

---

## 🏆 Key Learnings

✔ Built complete data pipeline from raw data to insights
✔ Applied Machine Learning for real-world prediction
✔ Created interactive dashboards for business decision-making
✔ Combined analytics + ML for end-to-end solution

---

## 👑 Author

**Ayush Chaudhary**
Aspiring Data Analyst | Machine Learning Enthusiast

---
