# 📱 Mobile Sales Dashboard (Power BI)
![Dashboard Preview](screenshot.png)
## Overview
This project is a **Power BI Dashboard** designed to analyze **mobile sales performance**.  
It provides insights into **total sales, quantities, transactions, customer ratings, brands, and payment methods**.  

The dashboard enables stakeholders to track **KPIs, trends by time, brand comparisons, and customer behavior** for better decision-making.

---

## Features
- **KPI Cards** → Total Sales, Quantity, Transactions, and Average Sales  
- **Time Analysis** → Sales & quantity breakdown by month and day  
- **Brand & Model Insights** → Compare performance across top mobile brands and models  
- **Customer Ratings** → Distribution of satisfaction levels (1–5 stars)  
- **Geographical Analysis** → City-level sales on a world map  
- **Payment Methods** → Transactions split across UPI, Debit Card, Credit Card, and Cash  
- **Filters** → Slicers for month, brand, mobile model, payment method, and day  

---

## Key Insights
### 📊 Performance
- **Total Sales**: 769M  
- **Total Quantity**: 19K  
- **Transactions**: 4K  
- **Average Sales**: 40K per transaction  

### 🏷️ Brand Insights
- **Top Brand by Sales**: Apple (1.61B)  
- Other major contributors: Samsung (1.60B), OnePlus (1.53B), Vivo (1.50B), Xiaomi (1.43B).  

### 📱 Mobile Models
- **iPhone SE** (60M), **OnePlus Nord** (58M), and **Galaxy Note** (56M) are the top-selling models.  

### 📆 Time Trends
- **Highest sales** on weekends (Saturday: 115M).  
- Sales gradually decrease towards midweek (Wednesday: 105M).  
- Quantities peak in **March (1696 units)** and **July (1700 units)**.  

### 🌍 Geography
- Strong presence in Indian cities like **Delhi, Mumbai, Ranchi, and Rajkot**.  

### 💳 Payment Behavior
- Transactions are spread across:  
  - **Credit Card (25.89%)**  
  - **Cash (25.03%)**  
  - **Debit Card (26.25%)**  
  - **UPI (22.83%)**  

### ⭐ Customer Satisfaction
- Majority of customers rated **5 stars (311)**.  
- Very few **1-star ratings (67)** → overall high satisfaction.  

---

## Tech Stack
- **Tool**: Power BI Desktop  
- **Dataset**: Mobile Sales Dataset  
- **Techniques**:  
  - Data cleaning & transformations  
  - DAX measures for KPIs  
  - Time-series trend analysis  
  - Geo-mapping  
  - Interactive slicers & filters  

---

## Repository Structure
```bash
Mobile-Sales-Dashboard/
├── data/                # Dataset (if shareable)
├── dashboard.pbix       # Power BI file
├── README.md            # Documentation
└── images/              # Dashboard screenshots
