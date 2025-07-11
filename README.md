# Ecommerce_Sales_Analysis
## 📊 Project Overview

### 🔹 Part 1: Data Cleaning & Basic Exploration
- Handled missing values (especially `CustomerID`)
- Removed duplicates
- Filtered out negative `Quantity` and `UnitPrice`
- Created `TotalSales` column = `Quantity` × `UnitPrice`
- Basic KPIs:
  - Total Revenue
  - Average Order Value
  - Total Transactions
  - Top Products by Sales

### 🔹 Part 2: Trend & Geographic Analysis
- 🗓 Monthly revenue trend using `InvoiceDate`
- 🌍 Country-wise revenue analysis
- 📦 Top-selling products (bar chart)
- 📈 Time series resampling using `resample('M')`

---

## 📂 Files Included

- `OnlineRetail.zip` — The dataset (compressed)
- `ecommerce_analysis.ipynb` — Jupyter/Colab notebook with code
- `README.md` — Project overview

---

## 🚀 How to Run

1. Clone the repo or open the notebook in Google Colab
2. Upload and unzip `OnlineRetail.zip`
3. Run the notebook cells

---

## 📌 Requirements

```bash
pandas
matplotlib
plotly
