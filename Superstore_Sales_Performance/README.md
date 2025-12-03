# 📊 Superstore Sales Performance Dashboard — MS Excel Project

This project is an end-to-end **Sales Performance Dashboard** built using **Microsoft Excel**.  
It analyzes the Superstore dataset to uncover insights about **revenue trends, product performance, regional sales, customer segments, and top-selling products**.

---

## 📁 Dataset  
The dataset used for this project is the **Superstore Sales Dataset** from Kaggle.

🔗 **Dataset Source:**  
https://www.kaggle.com/datasets/vivek468/superstore-dataset-final

To replicate the dashboard, download the CSV file from the link above and import it into Excel.

---

## 🚀 Project Objectives

- Analyze **monthly and yearly revenue trends**
- Identify **top-performing categories and sub-categories**
- Understand **regional sales distribution**
- Compare **customer segments** by sales contribution
- Find the **Top 10 products** based on sales
- Build an **interactive Excel dashboard** with slicers for filtering

---

## 🛠 Tools & Technologies

- **Microsoft Excel**
- Pivot Tables  
- Pivot Charts  
- Slicers  
- Excel Table  
- Data Cleaning & Formatting  
- Calculated Columns (Year, Month, Profit Margin)

---

## 📌 Steps to Build This Dashboard

### **1. Data Import & Cleaning**
- Imported CSV using `Data → Get Data → From Text/CSV`
- Converted dataset into an Excel Table (`SalesData`)
- Fixed data types for dates, numbers, and currency fields
- Removed duplicates & blanks

### **2. Added Calculated Columns**
- `Year = YEAR([@Order Date])`
- `Month = TEXT([@[Order Date]],"mmm")`
- `OrderMonth = EOMONTH([@[Order Date]],-1)+1`
- `Profit Margin = [@Profit] / [@Sales]`

### **3. Data Analysis using PivotTables**
Created PivotTables for:
- Monthly Revenue Trend  
- Category & Sub-Category Performance  
- Region-wise Sales  
- Segment-wise Sales  
- Top 10 Products by Sales  

### **4. Visualization (Charts Included)**
- Line Chart → Monthly Revenue Trend  
- Clustered Column Chart → Category Sales  
- Bar Chart → Region Sales  
- Donut/Pie Chart → Segment Sales  
- Horizontal Bar Chart → Top 10 Products  

### **5. Dashboard Creation**
Designed a clean, modern dashboard with:
- KPI Cards:
  - Total Sales  
  - Total Profit  
  - Avg Profit Margin  
  - Total Orders  
- Interactive slicers for:
  - Year  
  - Category  
  - Region  
  - Segment  

All charts dynamically update based on slicer selection.

---

## 📸 Dashboard Preview

> *(Insert a screenshot of your dashboard here after uploading the Excel file.)*  
Example:

![Dashboard Screenshot](./images/dashboard.png)



---

## 🔍 Key Insights from the Dashboard

- Highest sales months identified through trend analysis  
- Technology category generates the highest revenue  
- West region contributes the largest portion of total sales  
- Consumer segment shows maximum order volume  
- Top 10 products significantly impact overall revenue  

---

## 🏆 What You Will Learn from This Project

- Cleaning and transforming raw data in Excel  
- Creating powerful PivotTables for analysis  
- Building dynamic and interactive dashboards  
- Using slicers to control multiple charts  
- Designing a visually professional Excel report  

---

## 📢 Author

**Mohammed Hayath RK**  
Excel | Data Analyst  
