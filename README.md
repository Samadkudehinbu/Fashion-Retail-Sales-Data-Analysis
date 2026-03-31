# 🛍️ Fashion Retail Sales Data Analysis

> An end-to-end Excel analytics project uncovering sales trends, product performance, and customer order behaviour across global fashion retail markets (2020–2024).

📝 **Non-technical read:** [Medium Article](https://medium.com/@kudehinbusamad/unveiling-fashion-trends-a-data-driven-dive-into-retail-sales-insights-146788d7a65c) | 💼 [LinkedIn](https://www.linkedin.com/in/abdulsamad-kudehinbu/) | 🌐 [Portfolio](https://sites.google.com/view/abdulsamadportfolio/home)

---

## 📖 Project Overview

This project analyses transactional data from a fashion retail business to understand what's driving sales, which products and regions dominate, and how customer preferences shape revenue. The analysis was conducted entirely in Microsoft Excel, from data cleaning through to an interactive multi-page dashboard.

---

## 🎯 Project Objectives

The analysis set out to answer the following business questions:

1. **What are the overall sales trends, and how have they evolved between 2020 and 2024?**
2. **Which regions and product categories are generating the most revenue?**
3. **How do payment methods, gender preferences, and product types influence sales?**
4. **What are the top-selling products, and what pricing or quantity patterns emerge across brands?**

---

## 🗂️ Dataset Overview

| Field | Description |
|---|---|
| `Date` | Transaction date (2020–2024) |
| `Product Name` | Name of the fashion item sold |
| `Product Type` | Cap, Hoodie, Joggers, Sneakers, T-shirt |
| `Brand` | Adidas, Essentials, New Era, Nike, Off-White, Puma, Supreme |
| `Gender` | Men, Women, Unisex |
| `Category` | Casual, Limited Edition, Sportswear, Streetwear |
| `Country` | UK, USA, Canada, Germany, Japan, India, Australia, etc. |
| `Quantity` | Units sold per transaction |
| `Unit Price ($)` | Price per item |
| `Amount ($)` | Total transaction value (Quantity × Unit Price) |
| `Payment Mode` | Card, Cash on Delivery, UPI, Wallet |

- **Total Records:** ~10,000 transactions
- **Time Span:** 2020 – 2024
- **Scope:** Sales activity across multiple countries, brands, and product categories

---

## 🧹 Data Preparation

Before analysis, the following data cleaning and transformation steps were applied in Excel:

- **Missing values:** Identified and handled null/blank fields across key columns
- **Standardisation:** Normalised product names, date formats, and currency values for consistency
- **Feature engineering:** Derived time-based columns — `Month` and `Day of Week` — to support trend analysis
- **Data validation:** Verified categorical consistency across Brand, Gender, Category, and Payment Mode fields

---

## 📊 Dashboard Preview

The final deliverable is a 3-page interactive Excel dashboard with slicers for year-based filtering (2020–2024).

<img width="1390" height="2512" alt="merge all" src="https://github.com/user-attachments/assets/2441d5ab-179a-486e-b80a-fe38f710489e" />

### Page 1 — Sales Overview
High-level KPIs, monthly sales trend, revenue by brand, revenue by category, and geographical sales distribution.

<img width="1393" height="835" alt="image 1" src="https://github.com/user-attachments/assets/feca0dce-10bc-4d4b-9e2a-b6f1246cb660" />


### Page 2 — Product Performance
Sales by product type, top 5 countries by products sold, top 5 products by revenue, products sold by category, and average unit price by brand.

<img width="1393" height="842" alt="image 2" src="https://github.com/user-attachments/assets/188db85a-c40f-40f8-b8d5-a88467a2d103" />


### Page 3 — Order Insights
Orders and quantity by payment method, daily orders trend, quantity by gender and category, and percentage of orders by gender and product type.

<img width="1390" height="839" alt="image 3" src="https://github.com/user-attachments/assets/f9917116-ad57-477b-b906-bb02395d24ce" />


---

## 🔍 Key Insights & Findings

### 💰 Revenue & Growth
- Total revenue hit **$5.5M** with **24.49% growth vs Prior Year**
- Total orders: **10,000** | Total quantity sold: **31,300** units | Avg unit price: **$175.1**

### 🌍 Regional Performance
- **UK, Japan, and India** led in total products sold across the top 5 markets
- Geographical spread indicates strong international demand beyond just Western markets

### 👗 Product & Category Performance
- **Streetwear** was the top revenue category at **$1.6M**, closely followed by Casual, Limited Edition, and Sportswear
- **Sneakers** dominated by product type at **$2.4M** in revenue
- Top 5 products by revenue: **Jordan 1 High ($714K), Nike Dunk Low ($663K), Nike Tech Fleece ($650K), Off-White Hoodie ($639K), Yeezy Boost 350 ($613K)**
- **Off-White** had the highest average unit price at **$184.5**, followed by Supreme at **$182.4**

### 👥 Customer & Order Behaviour
- **Weekend orders were consistently higher** across the full period
- **Wallet** was the most used payment method by order volume (8.7K orders); **Card** led by quantity (8.3K units)
- Gender split was relatively balanced, with Men slightly dominating T-shirts and Joggers; Streetwear was more evenly distributed

### 📅 Seasonal Trends
- Higher order volumes recorded during **summer and holiday periods**, pointing to seasonal demand cycles

---

## 💡 Business Recommendations

| Area | Recommendation |
|---|---|
| **Inventory Planning** | Pre-stock Sneakers, Hoodies, and Streetwear items ahead of summer and holiday peaks |
| **Regional Marketing** | Prioritise targeted campaigns for UK, Japan, and India — the top-performing markets |
| **Payment Experience** | Strengthen digital payment infrastructure (Wallet, UPI) to reduce friction at checkout |
| **Product Investment** | Double down on high-margin collaborations (Off-White, Supreme) and bestselling SKUs (Jordan 1, Nike Dunk) |
| **Weekend Campaigns** | Schedule promotions and flash sales around weekends to maximise order volume |

---

## ⚠️ Limitations

- The dataset lacks detailed **customer profiles**, making personalisation and cohort analysis difficult
- As a historical dataset, it may not capture **sudden shifts in fashion trends** or broader economic disruptions
- No **return or refund data** was available, so net revenue figures may differ from actual performance

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| **Microsoft Excel** | Data cleaning, transformation, analysis, and dashboard design |
| **Pivot Tables & Pivot Charts** | Aggregation and dynamic visualisation |
| **Slicers & Timelines** | Interactive filtering by year |

---

## 👤 Author

**Abdulsamad Kudehinbu** — Data Analyst & Business Intelligence Analyst

- 🌐 [Portfolio](https://sites.google.com/view/abdulsamadportfolio/home)
- 💼 [LinkedIn](https://www.linkedin.com/in/abdulsamad-kudehinbu/)
- ✍️ [Medium](https://medium.com/@kudehinbusamad)

---

> *"Numbers tell stories. And with the right insights, those stories can shape the future of retail."*
