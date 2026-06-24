# 🛒 Online Retail Data Analysis (EDA Project)

This project performs **Exploratory Data Analysis (EDA)** on a large e-commerce dataset to understand customer behavior, sales trends, and business insights.

---

## 📌 Dataset Overview

- Records: 541,909 transactions
- Features: 8 columns
- Source: Online Retail dataset

### Columns:
- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

---

## ⚙️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🧹 Data Cleaning

- Renamed column names for clarity
- Converted invoice date to datetime format
- Handled missing values:
  - Removed rows with missing Customer ID
- Removed invalid transactions (quantity ≤ 0)
- Converted customer ID to integer
- Standardized product descriptions (lowercase)

---

## 🔧 Feature Engineering

Created new features:
- **Amount Spent = Quantity × Unit Price**
- Year-Month
- Month
- Day of Week
- Hour of Purchase

---

## 📊 Exploratory Data Analysis

### 👥 Customer Analysis
- Identified top customers by number of orders
- Found highly active repeat customers

### 💰 Revenue Analysis
- Top customers contribute majority of revenue
- Spending is highly skewed (few customers dominate sales)

### 📅 Time Analysis
- Peak sales months: November & December
- Strong seasonal buying behavior

### 🌍 Country Analysis
- United Kingdom dominates sales (~major share)
- Other countries contribute smaller portions

---

## 📉 Visualizations

The project includes:

- 📊 Orders per Customer (Line Plot)
- 💰 Spending per Customer (Line Plot)
- 📅 Monthly Order Trends (Bar Chart)
- 📆 Day-wise Order Distribution (Bar Chart)
- 🌍 Country-wise Orders (Barh Chart)
- 📦 Unit Price Distribution (Box Plot)

---

## ❌ Data Issues Found

- Missing Customer IDs (~135k rows)
- Free products (unit price = 0)
- Negative quantity values (returns/cancellations)

---

## 📈 Key Insights

- Majority revenue comes from few loyal customers
- Sales peak during holiday season (Nov–Dec)
- UK is the primary market
- Customer behavior is highly skewed

---

## 🚀 Future Improvements

- RFM (Recency, Frequency, Monetary) analysis
- Customer segmentation using clustering
- Time series forecasting for sales
- Product recommendation system

---

## 👨‍💻 Author

Data Analyst Project by Patnala Nagendra Kumar
