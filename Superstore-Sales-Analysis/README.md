# Superstore Sales Analysis

### Project Overview
This project analyzes sales and profitability trends in the **Superstore dataset** using Python. It focuses on computing KPIs, understanding category- and region-level performance, identifying time-based patterns, and examining how discounts impact profitability.

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## Dataset
**Sample - Superstore.csv**  
Includes order details, customer information, product categories, sales amounts, profit margins, discounts, and shipping details.

---

## Data Cleaning & Feature Engineering
- Converted `Order Date` and `Ship Date` into datetime format.  
- Engineered new time-based features:  
  - **Year**  
  - **Month** (Period-based for time-series)  
- Checked for missing values and dataset summary.  
- Computed descriptive statistics for sales, quantity, discount, and profit.

---

## Key KPIs Computed
- **Total Sales**  
- **Total Profit**  
- **Number of Unique Orders**  
- **Total Customers**

---

## Analysis Performed

### **Category-Level Analysis**
- Total sales by category (Furniture, Office Supplies, Technology)

### **Regional-Level Analysis**
- Regional comparison of total sales and total profit (West, East, Central, South)

### **Time-Series Analysis**
- Monthly sales trend using line plot to understand seasonal changes

### **Profitability Analysis**
- **Discount vs Profit** scatterplot to identify profit-reducing discount levels

---

## Visualizations
- **Bar Chart:** Sales by Category  
- **Line Chart:** Monthly Sales Trend  
- **Bar Chart:** Sales & Profit by Region  
- **Scatter Plot:** Discount vs Profit  

---

## Key Insights
- **Technology** category demonstrates strong revenue and profitability.  
- High discounts are strongly associated with **reduced or negative profits**.  
- Monthly sales show noticeable **seasonal peaks and dips**.  
- The **West region** consistently leads in both sales and profit performance.

---

## Skills Demonstrated
- Data Cleaning  
- KPI Calculation  
- Time-Series Analysis  
- Data Visualization  
- Exploratory Data Analysis (EDA)  
- Business Insight Extraction  

---

## Files in This Folder
- `Superstore.ipynb`  
- `README.md`
