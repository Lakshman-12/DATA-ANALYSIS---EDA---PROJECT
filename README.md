# 🛒 E-Commerce Data Analysis Project

## 📌 Overview
This project performs **data cleaning, preprocessing, and exploratory data analysis (EDA)** on an e-commerce dataset using Python.

The goal is to extract meaningful insights such as:
- Customer purchasing behavior
- Monthly and daily sales trends
- Top customers by orders and spending
- Country-wise sales performance

---

## 📂 Dataset
- File: `data.csv`
- Encoding: `ISO-8859-1`
- Total records: 541,909 rows
- Features:
  - InvoiceNo
  - StockCode
  - Description
  - Quantity
  - InvoiceDate
  - UnitPrice
  - CustomerID
  - Country

---

## ⚙️ Technologies Used
- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🔧 Data Preprocessing Steps
- Renamed columns for better readability
- Converted `invoice_date` to datetime format
- Converted `cust_id` from float to integer
- Handled missing values using `dropna()`
- Removed negative quantity values
- Converted product descriptions to lowercase

---

## ➕ Feature Engineering
Created new columns:
- `amount_spent = quantity × unit_price`
- `year_month`
- `month`
- `day`
- `hour`

---

## 📊 Exploratory Data Analysis (EDA)

### 🔹 Customer Analysis
- Number of orders per customer
- Top customers by number of orders
- Top customers by money spent

### 🔹 Time-Based Analysis
- Monthly order trends
- Day-wise sales distribution
- Hourly order patterns

### 🔹 Country Analysis
- Orders per country
- Revenue per country

---

## 📈 Key Insights
- Majority of orders come from **United Kingdom**
- Some customers contribute significantly to total revenue
- Peak sales observed in specific months (e.g., November)
- Few products have zero price (free items)

---

## 📊 Visualizations
- Line plots for customer orders
- Bar charts for monthly sales
- Boxplots for price distribution
- Country-wise comparison charts

---

## 🚀 How to Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/ecommerce-analysis.git
