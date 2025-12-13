# 📊 Task-1: Data Immersion & Wrangling  
ApexPlanet Data Analytics Internship  

## ✅ Objective
To rapidly acquaint with the dataset and perform the first stage of the analytics workflow:  
**data acquisition → familiarization → profiling → cleaning → transformation → final cleaned dataset.**

---

## 📁 Files Included
|-------------------------------------|-----------------------------------------------------------------|
| File                                |              Description                                        |
|-------------------------------------|-----------------------------------------------------------------|
| `task1_cleaning.ipynb`              | Jupyter/Colab notebook with all Python data cleaning scripts    |
| `cleaned_sales_dataset.csv`         | Final, fully cleaned dataset ready for analysis                 |
| `data_dictionary.md`                | Explanation of every column in the dataset                      |
| `README.md`                         | Overview of Task-1 and cleaning workflow                        |
|-------------------------------------|-----------------------------------------------------------------|
---

## 🧹 Data Cleaning & Transformation Summary

### **1. Data Access & Familiarization**
- Loaded the sales transactions dataset  
- Checked shape, datatypes, column names  
- Observed a sample of raw data  

### **2. Data Quality Assessment**
- Missing Customer IDs  
- Incorrect / missing Total Amount values  
- Mixed date formats (dd/mm/yyyy, mm-dd-yyyy, dd-mm-yyyy)  
- Inconsistent country values (India, india, USA, Usa, U.K)  
- Inconsistent payment method formatting  
- Outliers in Quantity and Unit Price  

### **3. Cleaning Performed**
- Standardized Invoice Dates → `Invoice_Date_Clean`  
- Cleaned Country spellings → `Country_Clean`  
- Cleaned Payment modes → `Payment_Mode_Clean`  
- Recalculated Total Amount → `Total_Amount_Clean`  
- Assigned placeholders for missing Customer IDs → `Unknown_1`, `Unknown_2`, …  
- Removed duplicate rows  
- Converted DOB to datetime  
- Added new feature → `Customer_Age`  

### **4. Final Output**
The cleaned dataset is fully analysis-ready for **Task-2 (EDA & SQL Queries)**.

---

## 🎥 LinkedIn Video Summary
Your 3–5 min video should show:
1. Dataset loading  
2. Data issues identified  
3. How dates, totals, and categories were cleaned  
4. Feature engineering (Customer Age)  
5. Final cleaned dataset  

---

## 👩‍💻 Tools Used
- Python  
- Pandas  
- Google Colab / Jupyter  
- GitHub  

---

# 🎉 Task-1 Completed Successfully
