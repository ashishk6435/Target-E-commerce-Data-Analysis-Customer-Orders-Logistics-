# 📊 Target E-commerce Data Analysis (Brazil)

## 📌 Project Overview
This project analyzes Target’s Brazilian e-commerce dataset to uncover insights related to **order growth, customer behavior, logistics performance, and payment patterns**.  
The goal is to translate raw transactional data into **actionable business insights** that support operational and strategic decision-making.

---

## 🗂️ Dataset Description
The analysis is based on a relational e-commerce dataset consisting of multiple tables:

- **customers** – customer demographics and location
- **orders** – order lifecycle timestamps
- **order_items** – product-level details and freight values
- **payments** – payment methods, values, and installments
- **products, sellers, reviews** – supporting dimensions

📅 **Time Period:** 2016–2018  
⚠️ Note: Boundary months contain partial data and are handled carefully in trend analysis.

---

## 🛠️ Tools & Technologies
- **SQL (SQLite)** – data extraction, joins, aggregations, time-based analysis  
- **Python** – Pandas, NumPy for EDA and validation  
- **Power BI** – interactive dashboards and storytelling  
- **Jupyter Notebook** – analysis workflow  

---

## 🔍 Key Analyses Performed

### 1️⃣ Order Growth & Trend Analysis
- Identified **~9× growth in order volume during 2017**
- Observed **demand stabilization in 2018**, indicating market maturity
- Isolated real growth by excluding incomplete months

---

### 2️⃣ Monthly Seasonality
- Clear **mid-year seasonality (March–August)** with higher order volumes
- Lower activity during early and late months of the year

---

### 3️⃣ Time-of-Day Ordering Behavior
Orders were categorized into:
- Dawn (0–6 hrs)
- Morning (7–12 hrs)
- Afternoon (13–18 hrs)
- Night (19–23 hrs)

📌 **Insight:**  
Most orders are placed during **Afternoon and Night hours**, suggesting higher customer engagement outside working hours.

---

### 4️⃣ Regional (State-level) Analysis
- Strong concentration of orders in a few high-volume states
- Significant **regional disparities in delivery time**
- Northern states show **3× higher average delivery times** compared to southern regions

---

### 5️⃣ Delivery Performance
- Calculated:
  - Delivery time (Purchase → Delivered)
  - Difference between **actual vs estimated delivery**
- Identified states delivering orders **20–45 days earlier than promised**, indicating conservative estimates or strong logistics performance

---

### 6️⃣ Payment Behavior Analysis
- **Credit cards dominate** monthly order volumes
- **UPI shows a significant and consistent secondary share**
- Majority of orders are paid in **single installments**, though multi-installment payments remain relevant

---

## 📈 Business Insights Summary
- Rapid growth phase followed by stable demand indicates a maturing platform
- Logistics performance varies heavily by geography
- Delivery estimates can be optimized in high-performing states
- Payment flexibility (UPI, installments) plays a key role in customer adoption

---

## 📊 Dashboards
Interactive Power BI dashboards were built to visualize:
- Order growth trends
- Delivery SLA performance
- Regional demand distribution
- Payment method adoption

---

## 🚀 Key Recommendations
- Optimize logistics for high-delay regions
- Recalibrate delivery estimates where early delivery is consistent
- Align promotions and infrastructure with peak ordering hours
- Strengthen UPI payment experience to improve conversions
- Maintain installment flexibility for high-value purchases

---

## 📁 Repository Structure
