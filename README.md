# 🛍️ Market Analysis Report for a National Clothing Chain

> *"I always wondered — what if we could predict what each customer really wants, even without knowing their income?"*

Faced with stagnant sales, a national clothing retailer needed actionable insights to optimize their marketing strategy. This project aimed to analyze various data sources — including census data, customer behavior, and product performance — to determine **which product to advertise to each customer**, in order to **maximize engagement and profitability**.

---

## 📦 Dataset Overview

This project combines multiple sources of data:
- **Customer Data**: Demographics, location, and purchase history
- **Product Data**: Inventory, prices, ratings, and return rates
- **Census Data**: Average income, population, industry per location
- **Additional Data**: Weather, economy, and local competition

Using these datasets, the analysis estimates customer income, identifies patterns in purchase behavior, and correlates product performance with satisfaction indicators.

---

## ❓ Key Business Questions

1. 📈 What is the correlation between **sales** and **income**?
2. 💬 How are **customer ratings** linked to **product return rates**?
3. 🔍 Can we **predict income** based on **sales behavior** and **location**?
4. 👤 Which customer is predicted to have the **highest income**?
5. 👜 Which product should be advertised the most?

---

## 🧹 Analysis Workflow

- Merged customer, product, and external datasets using location as a key.
- Estimated customer income via regression models based on location and purchase data.
- Analyzed product ratings and return rates to detect quality issues.
- Visualized correlations and predicted outcomes using Power BI.

Key metrics and visuals include:
- Income vs Sales scatter plots
- Return rates by customer/product
- Predicted income per customer & per region
- Product recommendation maps

---

## 📊 Key Insights

### 1️⃣ Correlation between sales and income
> ✅ A strong **positive correlation (R² ≈ 0.84)** was observed. High-income areas tend to generate more sales.

### 2️⃣ Customer ratings vs return rate
> 🔄 Negative correlation found: **Lower-rated products had higher return rates**, suggesting dissatisfaction.

### 3️⃣ Predicting income from sales
> 📊 Using linear regression, we modeled income from location and purchase history with meaningful accuracy.

### 4️⃣ Customer with highest predicted income
> 💼 A small group of customers stood out with significantly high estimated income, useful for targeting premium products.

### 5️⃣ Most advertised product
> 👜 **Leather Bags ($1000)** were recommended to high-income, low-return customers.  
> 👕 **Shirts ($25)** for budget-conscious, price-sensitive segments.

---

## 🛠 Built With

- **Microsoft Power BI**
- **Excel**
- **Linear Regression Models**
- **Data Merging & Cleaning (Power Query / Excel)**

---

## 📁 Files in This Repository

- `National-Clothing-Chain-Report.pdf` — Full analysis report
- `National-Clothing-Chain-Summary.doc` — Executive summary
- `National-Clothing-Chain-Data-Model.png` — Data model diagram
- `/img/` — All related visualizations (correlations, income maps, product stats)

---

## 🧠 Final Thought

This project demonstrates the **power of data in guiding marketing strategy**. Even without direct access to income data, we used public datasets and customer behavior to infer valuable insights — turning raw data into informed business decisions.

