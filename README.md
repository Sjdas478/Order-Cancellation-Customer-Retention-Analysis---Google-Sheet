# Order-Cancellation-Customer-Retention-Analysis---Excel/Google Sheet
**Tool Used:** Google Sheets  
**Duration:** 3 Days  
**Type:** Mock Business Case | Individual Project

---

## 🎯 Objective

To analyze customer order cancellations and segment customer behavior using RFM analysis. The goal was to identify business losses, customer satisfaction risks, and design a basic customer retention strategy using only Google Sheets.

---

## 📁 Dataset

- **Order Data Sheet:** Raw unstructured order details of top customers (customer name, food item, quantity, date, payment method, status, feedback)
- **Details Sheet:** Food item catalog with prices and categories (Veg/Non-Veg)

---

## 🧼 Data Cleaning

- Used `SPLIT`, `TRIM`, `TEXT`, and `DATE` functions to clean semi-structured string data
- Parsed customer names, addresses, delivery agents, food items, feedbacks into usable columns
- Standardized cancellation reasons for analysis

---

## 📊 Key Dashboards Built

### ✅ Sales Dashboard (using Pivot Tables)

- **Total Sales:** ₹9.4 Lakhs  
- **Orders:** 1,642  
- **Operational Areas:** 10  
- **Customers:** 41  
- **Average Order Value:**  
  - Non-Veg: ₹810  
  - Veg: ₹373  
- **Cancellation Rate:** 26.63%
- Monthly Order Trends, Area-wise Sales, Category-wise Breakdown

---

## ❌ Cancellation Analysis

- **Total Loss:** ₹1.13 lakh due to:
  - Delayed Delivery (highest loss)
  - Payment Issues
  - Out of Stock, App Glitches
- Built dynamic dropdown system to filter by area and reason

---

## 📈 RFM Segmentation

- Used Recency, Frequency, and Monetary scoring to group customers into:
  - **Top-tier Customers**
  - **Loyal Customers**
  - **At-Risk / Potential Loyal Customers**

---

## 🔄 Last 5 Orders Status Analysis

- Created custom logic to track **delivery status of last 5 orders per customer**
- Flagged customers with **3+ consecutive cancellations** as **high-risk**
- Mapped feedback reasons to cancellation patterns

---

## 💬 Retention Strategy System

- Used conditional logic to auto-generate **personalized re-engagement messages**
  - Example: *“You are our most valued customer! We've improved our delivery process for faster service. Enjoy 10% off your next order as a thank you for your patience!”*
- Built a separate dashboard tab for retention actionables

---

## 💡 Key Outcomes

- Identified ₹1.13L+ in preventable revenue loss
- Mapped top problematic delivery areas and customer issues
- Built a basic but scalable churn detection and messaging system inside Google Sheets

---

## 📌 View Project

- [🔗 Google Sheet (View-only)](https://docs.google.com/spreadsheets/d/1-S_l6GLugReABz6K-RDzzj5lNrK7sIqg18QoMELDnc4/edit?usp=sharing)
