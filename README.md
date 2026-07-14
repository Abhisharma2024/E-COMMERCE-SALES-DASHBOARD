# 🛒 E-Commerce Sales Dashboard | Power BI

<p align="center">

![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-Data-blue?style=for-the-badge&logo=mysql)
![Excel](https://img.shields.io/badge/Excel-Data%20Cleaning-217346?style=for-the-badge&logo=microsoft-excel)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

</p>

---

# 📌 Project Overview

The **E-Commerce Sales Dashboard** is an interactive business intelligence solution developed using **Microsoft Power BI** to monitor and analyze online sales performance. The dashboard provides valuable insights into revenue, customer behavior, product performance, order trends, payment methods, shipping locations, ratings, cancellations, and returns.

This dashboard helps business owners and decision-makers identify growth opportunities, optimize operations, and improve customer satisfaction through data-driven insights.

---

# 🎯 Business Objectives

- Monitor overall sales performance
- Track revenue and order trends
- Analyze customer purchasing behavior
- Compare product category performance
- Evaluate shipping locations
- Monitor order status distribution
- Analyze payment method preferences
- Identify cancellation and return rates
- Improve business decision making

---

# 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Microsoft Power BI | Dashboard Development |
| Power Query | Data Cleaning & Transformation |
| DAX | Measures & KPIs |
| Excel / CSV | Data Source |
| Data Modeling | Relationship Building |

---

# 📂 Dashboard KPIs

The dashboard displays the following key performance indicators:

| KPI | Value |
|------|--------|
| Total Revenue | 31.55M |
| Total Orders | 50K |
| Total Customers | 12K |
| Average Order Value | 630.96 |
| Average Rating | 2.99 |
| Cancellation Rate | 0.11% |
| Return Rate | 0.11% |

---

# 📈 Dashboard Visualizations

## 1️⃣ KPI Cards

Displays overall business performance including:

- Total Revenue
- Total Orders
- Total Customers
- Average Order Value
- Average Rating
- Cancellation %
- Return %

---

## 2️⃣ Revenue by Product Category

Visualizes revenue generated from different product categories.

Categories include:

- Electronics
- Books
- Beauty
- Clothing
- Home
- Sports
- Toys
- Apparel

Purpose:

- Identify best-selling categories
- Compare product performance
- Improve inventory planning

---

## 3️⃣ Monthly Revenue Trend

Shows revenue trend over time.

Benefits:

- Monthly sales comparison
- Seasonal trend analysis
- Growth monitoring

---

## 4️⃣ Review Rating Analysis

Analyzes customer ratings against discount percentage.

Insights:

- Effect of discounts on ratings
- Customer satisfaction trends
- Product quality evaluation

---

## 5️⃣ Average Order Value by Shipping Country

Compares average order value across countries.

Countries:

- USA
- UK
- India
- Canada

Purpose:

- International sales analysis
- Market comparison
- Shipping performance

---

## 6️⃣ Average Order Value by Shipping City

Displays cities generating higher average order values.

Example Cities:

- New York
- Los Angeles
- Pune
- Chennai

Purpose:

- Regional sales analysis
- City-wise performance tracking

---

## 7️⃣ Order Status Distribution

Shows order counts based on status.

Statuses:

- Delivered
- Pending
- Refunded
- Returned

Purpose:

- Fulfillment monitoring
- Delivery performance
- Operational efficiency

---

## 8️⃣ Customer Revenue Table

Displays top customers along with total revenue generated.

Purpose:

- Identify loyal customers
- Customer segmentation
- Revenue contribution analysis

---

## 9️⃣ Payment Method Analysis

Compares payment methods with order status.

Payment Methods:

- UPI
- Credit Card
- Debit Card
- COD
- Wallet
- Net Banking
- PayPal

Purpose:

- Customer payment preference
- Transaction analysis
- Payment performance

---

# 🎛 Interactive Filters

The dashboard includes multiple slicers for dynamic analysis.

Available filters:

- Year
- Month
- Product Category
- Payment Method

Users can interact with these slicers to perform customized business analysis.

---

# 📊 Data Analysis Performed

✔ Data Cleaning

- Removed duplicates
- Handled missing values
- Standardized formats
- Corrected data types

✔ Data Transformation

- Created calculated columns
- Generated DAX measures
- Built relationships
- Optimized model

✔ Data Visualization

- KPI Cards
- Column Charts
- Line Charts
- Donut Charts
- Scatter Plot
- Bar Charts
- Matrix Table
- Slicers

---

# 📌 DAX Measures Used

Examples include:

```DAX
Total Revenue = SUM(Orders[Revenue])

Total Orders = COUNT(Orders[OrderID])

Total Customers = DISTINCTCOUNT(Orders[CustomerID])

Average Order Value =
DIVIDE([Total Revenue],[Total Orders])

Average Rating =
AVERAGE(Orders[ReviewRating])

Cancellation % =
DIVIDE(
CALCULATE(COUNT(Orders[OrderID]),Orders[OrderStatus]="Cancelled"),
COUNT(Orders[OrderID])
)

Return % =
DIVIDE(
CALCULATE(COUNT(Orders[OrderID]),Orders[OrderStatus]="Returned"),
COUNT(Orders[OrderID])
)
```

---

# 💡 Business Insights

### Revenue Performance

- Revenue exceeded **31 Million**.
- Strong customer purchasing activity observed.

### Customer Behavior

- More than **12,000 unique customers**.
- Average customer rating around **3.0**.

### Product Performance

- Electronics and Beauty categories generated higher revenue.
- Clothing contributed comparatively lower sales.

### Order Fulfillment

- Majority of orders were successfully delivered.
- Very low cancellation and return percentages indicate operational efficiency.

### Payment Preferences

- Digital payment methods dominate customer transactions.
- COD still contributes significantly.

### Geographic Analysis

- USA generated the highest average order value.
- Major cities contributed consistently to revenue.

---

# 📈 Dashboard Features

✅ Modern UI Design

✅ Glassmorphism Theme

✅ Dynamic Slicers

✅ Interactive Charts

✅ KPI Cards

✅ Responsive Layout

✅ Business Insights

✅ Easy Navigation

---

# 📂 Folder Structure

```
E-Commerce-Sales-Dashboard/
│
├── Dashboard.pbix
├── Dataset.csv
├── Images/
│     Dashboard.png
├── README.md
└── Assets/
```

---

# 🚀 Future Improvements

- Customer Segmentation (RFM Analysis)
- Profit Analysis Dashboard
- Sales Forecasting
- AI Visuals
- Geographic Maps
- Drill-through Pages
- Tooltips
- Mobile Layout
- Incremental Refresh

---

# 👨‍💻 Author

**Abhishek Sharma**

**Aspiring Data Analyst**

### Skills

- Power BI
- SQL
- Python
- Excel
- Power Query
- DAX
- Data Cleaning
- Data Visualization
- Business Intelligence

---

# ⭐ If you found this project useful, don't forget to give it a Star!
