# 🛒 E-Commerce Data Analysis (EDA)

This project performs Exploratory Data Analysis (EDA) on an e-commerce dataset using Python.

## 📌 Project Overview
- Data Cleaning
- Handling Missing Values
- Feature Engineering
- Customer Analysis
- Sales Analysis
- Data Visualization

## 📂 Dataset
- File: `data.csv`
- Contains transaction details like:
  - Invoice Number
  - Product Description
  - Quantity
  - Price
  - Customer ID
  - Country

## ⚙️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 🧹 Data Cleaning Steps
- Renamed columns
- Converted `invoice_date` to datetime
- Handled missing values
- Removed negative quantities
- Converted `cust_id` to integer
- Standardized text data

## 📊 Feature Engineering
- Created `amount_spent`
- Extracted:
  - Year-Month
  - Month
  - Day
  - Hour

## 📈 Key Analysis
- Top customers by orders
- Top customers by spending
- Monthly sales trends
- Daily order distribution
- Country-wise orders and revenue

## 📉 Visualizations
- Orders per customer
- Money spent per customer
- Monthly sales trends
- Country-wise analysis

## ▶️ How to Run
```bash
pip install -r requirements.txt
