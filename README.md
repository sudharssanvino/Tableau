# Technical Document: Tableau Report for Amazon Sales

## 1. Report Overview

The **Amazon Sales Tableau Report** is designed to analyze sales performance, customer behavior, and operational trends. It provides management and business teams with key insights for decision-making by visualizing sales KPIs, product performance, customer segmentation, and profitability.

---

## 2. Data Sources

* **Primary Source:** Amazon sales transactions dataset (CSV/Database/Cloud data warehouse).
* **Supporting Sources:**

  * Product catalog (Category, Brand, Cost Price, Selling Price).
  * Customer details (Demographics, Location, Prime/Non-Prime).
  * Logistics & returns data (Delivery time, Returns, Refunds).
  * Marketing spend (optional, for ROI analysis).

---

## 3. Data Model

* **Fact Table:** Sales Transactions (Order ID, Product ID, Customer ID, Date, Revenue, Quantity, Discounts, Returns).
* **Dimension Tables:**

  * **Product Dimension:** Product Name, Category, Sub-Category, Brand.
  * **Customer Dimension:** Customer ID, Segment, Region, Prime/Non-Prime.
  * **Date Dimension:** Order Date, Month, Quarter, Year.
  * **Geography Dimension:** Country, State, City, Zip Code.

---

## 4. Key Performance Indicators (KPIs)

### Sales Performance

* Total Sales (Revenue)
* Total Orders
* Total Quantity Sold
* Average Order Value (AOV) = Revenue / Number of Orders
* Sales Growth % (MoM, QoQ, YoY)

### Profitability

* Gross Profit = Revenue – Cost of Goods Sold (COGS)
* Profit Margin % = Profit / Revenue × 100
* Top 10 Most Profitable Products
* Low Margin / Loss-making Products

### Customer Insights

* Total Customers
* New vs. Returning Customers
* Customer Lifetime Value (CLV)
* Customer Retention Rate
* Prime vs. Non-Prime Customer Sales

### Product & Category Trends

* Best-Selling Products by Revenue & Quantity
* Category-Wise Contribution to Revenue
* Stock-Out & Inventory Gap Analysis (if stock data is available)
* Product Return Rate %

### Marketing & Operations

* Discount Impact on Sales (With vs. Without Discounted Orders)
* Campaign ROI (if marketing data available)
* Delivery Performance (On-time %, Avg. Delivery Days)
* Return/Refund Trends

---

## 5. Visualizations & Dashboards

1. **Executive Summary Dashboard**

   * KPI Tiles: Revenue, Profit, Orders, AOV, Retention Rate
   * Trend Line: Sales & Profit over Time
   * Map: Sales by Region

2. **Sales & Product Dashboard**

   * Bar Chart: Top 10 Products by Sales
   * Tree Map: Category Contribution
   * Line Graph: Sales Trend by Category/Brand

3. **Customer Insights Dashboard**

   * Pie Chart: Prime vs. Non-Prime Customers
   * Line Chart: New vs. Returning Customers over Time
   * Heatmap: Sales by Customer Segment & Region

4. **Profitability Dashboard**

   * KPI Card: Profit Margin %
   * Scatter Plot: Revenue vs. Profit by Product
   * Bar Chart: Loss-Making Products

5. **Operational Dashboard**

   * KPI Tiles: Delivery SLA %, Return Rate %
   * Line Chart: Refund Trends over Time
   * Histogram: Delivery Days Distribution

---

## 6. Filters & Parameters

* Date Range Selector (Daily, Weekly, Monthly, Quarterly, Yearly)
* Region / Country / City Filter
* Product Category & Sub-Category Filter
* Prime / Non-Prime Customers
* Discounted vs. Non-Discounted Orders

---

## 7. User Roles & Access

* **Executives / Leadership:** Access to all dashboards (high-level KPIs & summaries).
* **Sales & Marketing Team:** Access to product, customer, and campaign performance dashboards.
* **Operations Team:** Access to delivery, return, and logistics dashboards.

---

## 8. Expected Insights

* Identify high-performing categories and underperforming products.
* Understand customer buying patterns and loyalty.
* Evaluate profitability and optimize pricing/discount strategies.
* Track delivery efficiency and return/refund issues.
* Support data-driven decision-making for Amazon sales strategy.

---
