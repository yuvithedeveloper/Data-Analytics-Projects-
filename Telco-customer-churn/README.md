# Telco Customer Churn Analysis

### Project Overview
This project analyzes customer churn behavior in the Telco dataset using Python. The goal is to identify key factors that influence customer churn through data cleaning, transformation, exploratory data analysis (EDA), and visualization.

---

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Dataset
**WA_Fn-UseC_-Telco-Customer-Churn.csv**  
Contains customer demographics, service details, contract types, and churn labels.

---

## Data Cleaning & Preprocessing
- Handled missing values and corrected invalid entries.
- Converted **TotalCharges** from string to numeric.
- Imputed missing values using median.
- Encoded binary categorical variables (Yes/No → 1/0).
- Dropped irrelevant identifiers like `customerID`.

---

## Exploratory Data Analysis (EDA)
### Visualizations included:
- **Churn Distribution**  
- **Monthly Charges vs Churn**
- **Tenure vs Churn**
- **Churn by Contract Type**
- **Churn by Internet Service**
- **Correlation Heatmap**

---

## Key Insights
- Customers with **month-to-month contracts** churn the most.
- Higher **monthly charges** are strongly associated with churn.
- **Long-tenure customers** are less likely to churn.
- Fiber optic users show higher churn rates compared to DSL users.

---

## Skills Demonstrated
- Data Cleaning  
- Feature Engineering  
- EDA & Visualization  
- Business Insight Extraction

---

## Files in This Folder
- `Telco.ipynb`
- `README.md`
