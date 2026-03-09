# ARTI308 – Lab 3: Exploratory Data Analysis (EDA)

## Dataset: Chocolate Sales

**Source:** Provided dataset (CSV format)  
**Rows:** 3,282 | **Columns:** 6  
**Date Range:** January 2022 – August 2024  

### Columns Description

| Column | Type | Description |
|---|---|---|
| `Sales Person` | Categorical | Name of the salesperson |
| `Country` | Categorical | Country where the sale occurred |
| `Product` | Categorical | Name of the chocolate product |
| `Date` | DateTime | Date of the transaction |
| `Amount` | Numerical | Revenue generated ($) |
| `Boxes Shipped` | Numerical | Number of boxes shipped |

---

## Machine Learning Problem

This dataset is suitable for a **Regression** problem.  
**Goal:** Predict the `Amount` (revenue) of a chocolate sale based on features such as country, product, salesperson, and boxes shipped.

**Target Variable:** `Amount`  
**Problem Type:** Supervised Learning – Regression

---

## EDA Key Findings

- **No missing values** and **no duplicate rows** found in the dataset
- Both `Amount` and `Boxes Shipped` follow a **right-skewed distribution**
- There is a **moderate positive correlation** between boxes shipped and revenue
- Revenue varies significantly across **countries** and **products**
- **Monthly revenue trend** shows seasonal fluctuations between 2022–2024

---

## Repository Contents

| File | Description |
|---|---|
| `README.md` | This summary file |
| `Chocolate_Sales.csv` | The dataset used in the analysis |
| `3-_EDA_Solved.ipynb` | Full EDA Jupyter Notebook with code, visualizations, and written analysis |
