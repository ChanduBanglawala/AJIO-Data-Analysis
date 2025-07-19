# 🛍️ AJIO E-commerce Data Analysis Using Python

This project is part of a masterclass by **WsCube Tech**, where I performed end-to-end data analysis on AJIO’s e-commerce data. It includes transaction, product, customer, and return data — over **10,000+ real-world records**.

---

## 📌 Objectives

- Understand customer purchase behavior
- Analyze product sales and categories
- Identify return/refund trends
- Discover top-performing locations and delivery patterns
- Visualize payment preferences and reward systems

---

## 🗃️ Dataset Description

### 1. `Orders.csv`
- `Or_ID`, `C_ID`, `P_ID`, `Order_Date`, `Order_Time`, `Qty`, `Coupon`, `DP_ID`, `Discount`

### 2. `Products.csv`
- `P_ID`, `P_Name`, `Category`, `Company_Name`, `Gender`, `Price`

### 3. `Returns.csv`
- `RT_ID`, `Or_ID`, `Reason`, `Return_Refund`, `Dates`

### 4. `Transactions.csv`
- `Tr_ID`, `Or_ID`, `Transaction_Mode`, `Reward`

---

## 📊 Key Insights & Visualizations

- 🧑‍🤝‍🧑 **Customer Age Distribution** bar chart with spacing
- 📈 Top-selling product categories & price range
- 🛍️ Gender-based purchase trends
- 💳 Popular payment methods
- 🧾 Most common refund reasons
- 🌆 Top 10 cities with highest orders
- 📦 Analysis of delivery partners (`DP_ID`)
- 🎁 Usage of coupons vs discounts
- 📆 Time-series trend of orders

---

## 🧰 Technologies Used

- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**
