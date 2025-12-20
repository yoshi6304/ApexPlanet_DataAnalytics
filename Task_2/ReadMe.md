# 📊 Task-2: Exploratory Data Analysis (EDA) & Business Intelligence  
**ApexPlanet Data Analytics Internship**

---

## 🎯 Objective
The objective of this task is to perform **in-depth exploratory data analysis** on the cleaned dataset from Task-1, extract **actionable business insights**, apply **SQL for analytical querying**, and present findings through a **static dashboard mock-up** suitable for business stakeholders.

---

## 📁 Repository Structure
Task-2/
├── eda_analysis.ipynb
├── sql_queries.sql
├── dashboard_mockup.pdf
└── README.md


---

## 🔍 Dataset Overview
- Source: Cleaned sales transactions dataset from Task-1  
- Records analyzed after data cleaning and preprocessing  
- Dataset includes customer details, product categories, sales values, payment methods, and geographical information  

---

## 📈 Analysis Performed

### 🔹 1. Exploratory Data Analysis (EDA)
EDA was conducted using Python to understand data distributions and patterns.

**Key activities:**
- Dataset profiling (`info()`, `describe()`)
- Univariate analysis of:
  - Customer Age
  - Quantity purchased
  - Total revenue
- Visualization of:
  - Orders by product category
  - Revenue by product category
  - Country-wise order distribution
  - Payment method usage
  - Monthly sales trend

📌 *Purpose:* To identify dominant categories, customer behavior, and overall sales performance.

---

### 🔹 2. SQL-Based Business Analysis
SQL queries were executed using **SQLite within Python** to answer key business questions.

**Business questions addressed:**
- Which product categories generate the highest revenue?
- How does revenue vary month-wise?
- Which countries contribute most to total sales?
- What are the most preferred payment methods?
- What is the average order value per product category?
- How does revenue vary across customer age groups?

📌 *Purpose:* To demonstrate the ability to extract structured insights using SQL aggregation and filtering techniques.

---

### 🔹 3. Multivariate Analysis & Correlation
To explore relationships between numerical variables, multivariate analysis was performed.

**Techniques used:**
- Correlation matrix and heatmap
- Scatter plots:
  - Quantity vs Total Revenue
  - Customer Age vs Total Spending

📌 *Key finding:*  
A strong positive correlation was observed between quantity and total revenue, validating revenue calculations and purchase behavior.

---

### 🔹 4. Static Dashboard Mock-up
A **static dashboard** was designed to visually summarize the analysis outcomes.

**Dashboard includes:**
- Key Performance Indicators (KPIs):
  - Total Revenue
  - Total Orders
  - Average Order Value
  - Top Product Category
  - Top Country
- Visual summaries:
  - Monthly sales trend
  - Revenue by product category
  - Orders by country
  - Payment method distribution

📌 *Purpose:* To present insights in a concise and decision-maker-friendly format.

---

## 🛠️ Tools & Technologies
- **Python** (Pandas, Matplotlib, Seaborn)
- **SQL** (SQLite via Python)
- **Google Colab**
- **GitHub**
- **Google Slides / PowerPoint** (for dashboard mock-up)

---

## ✅ Key Outcomes
- Identified top-performing product categories and regions
- Analyzed customer demographics and spending patterns
- Applied SQL for real-world business analysis
- Created a dashboard-style summary of insights

---

## 🚀 Conclusion
Task-2 successfully demonstrates a complete **analytical workflow** — from data exploration and SQL querying to insight generation and dashboard presentation — laying a strong foundation for advanced analytics and visualization tasks in the upcoming stages of the internship.
