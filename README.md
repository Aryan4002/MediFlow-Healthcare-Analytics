# 🏥 MediFlow Healthcare Analytics Dashboard

## 📌 Project Overview

This project focuses on analyzing **hospital resource utilization and patient readmission patterns** using data analytics techniques. The objective is to identify high-risk patient groups, optimize hospital resources, and support data-driven healthcare decisions.

The project simulates a real-world healthcare analytics system and provides insights through an interactive dashboard.

---

## 🎯 Objectives

* Analyze **patient readmission rates**
* Identify **high-risk age groups and diseases**
* Evaluate **department-wise hospital performance**
* Optimize **resource utilization and cost distribution**
* Visualize insights using an **interactive Power BI dashboard**

---

## 🛠️ Tech Stack

* **Python (Pandas, Matplotlib, Seaborn)** – Data preprocessing & analysis
* **SQLite** – SQL-based data querying
* **Power BI** – Data visualization & dashboard creation
* **Google Colab** – Development environment

---

## 📂 Project Structure

```
MediFlow_Project/
│
├── data/
│   └── patient_data_cleaned.csv
│
├── notebooks/
│   └── MediFlow_Project.ipynb
│
├── outputs/
│   └── final_dashboard_data.csv
│
├── dashboard/
│   └── PowerBI_Dashboard.pbix
│
└── README.md
```

---

## 🔄 Workflow

1. **Data Preparation**

   * Generated synthetic healthcare dataset
   * Cleaned and structured data using Python

2. **Data Processing**

   * Loaded dataset into SQLite database
   * Executed SQL queries for analysis

3. **Data Analysis**

   * Performed exploratory data analysis (EDA)
   * Created derived features like *length of stay* and *age groups*

4. **Visualization**

   * Built an interactive Power BI dashboard
   * Added KPIs, charts, filters, and map visual

---

## 📊 Dashboard Features

* 📌 KPI Cards:

  * Total Patients
  * Average Length of Stay
  * Readmission Rate
  * Average Cost

* 📊 Visualizations:

  * Readmission Rate by Department
  * Readmission Rate by Disease
  * Readmission by Age Group
  * Cost Analysis by Department
  * Patient Distribution by Location (Map)

* 🎛️ Filters:

  * Department
  * Disease
  * Age Group
  * Location

---

## 🔍 Key Insights

* Patients aged **60–80** show higher readmission risk
* Certain departments (e.g., Cardiology) have higher readmission rates
* Longer hospital stays are correlated with increased readmissions
* Cost distribution varies significantly across departments
* Patient distribution shows regional concentration patterns

---

## 📸 Dashboard Preview

*(Add screenshots here)*

---

## 🚀 How to Run the Project

1. Open the notebook in **Google Colab**
2. Upload `patient_data_cleaned.csv`
3. Run all cells for analysis
4. Open Power BI file to view dashboard

---

## 🧠 Learnings

* End-to-end data analytics workflow
* SQL-based data querying and transformation
* Data visualization best practices
* Healthcare data analysis concepts

---

## 🔮 Future Improvements

* Integration with real-time hospital data
* Deployment using cloud platforms (AWS)
* Machine learning model for readmission prediction

---

## 👨‍💻 Authors

Aryan Tomar
Sangeetha Balasubramani
Shyam Mondal
Harshal Nakade

## 📌 Note

This project uses **synthetic data** for demonstration purposes and does not contain real patient information.
