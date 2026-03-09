# 📊 Sales Performance & Insights Dashboard

A comprehensive, interactive data visualization tool built to analyze retail sales performance—focusing on revenue trends, product categories, regional performance, and profit margins.

---

## 1. Project Purpose
The **Sales Data Analysis Dashboard** is designed to transform raw transactional data into actionable business intelligence. It allows stakeholders to monitor key performance indicators (KPIs) and identify growth opportunities across different product lines and geographic regions. This tool is intended for sales managers, retail analysts, and business owners who need to make data-driven decisions to optimize inventory and marketing strategies.

## 2. Tech Stack
* **📊 Power BI Desktop** – Primary platform for data visualization and report design.
* **📂 Power Query** – Utilized for ETL (Extract, Transform, Load) processes, cleaning messy sales records, and formatting date/currency fields.
* **🧠 DAX (Data Analysis Expressions)** – Used to create sophisticated measures such as Year-over-Year (YoY) growth, Total Revenue, Profit Margins, and Top-performing products.
* **📝 Data Modeling** – Established a Star Schema involving Fact tables (Sales) and Dimension tables (Products, Customers, Regions, and Calendar) to ensure high performance and accurate cross-filtering.

## 3. Data Source
* **Source:** The dataset includes historical sales transactions, product catalogs, and customer demographic information.
* **Structure:** The data covers multiple years of transactions, detailing:
    * **Sales:** Quantity sold, unit price, discounts, and order dates.
    * **Products:** Category, sub-category, and SKU details.
    * **Geography:** Country, State, and City level data.

## 4. Features / Highlights

### 🔴 Business Problem
Retail businesses often struggle to see the "big picture" when buried in spreadsheets. Identifying which products are underperforming or which regions are driving the most profit is time-consuming without a centralized visual hub.

### 🎯 Goal of the Dashboard
* To provide a high-level overview of sales health at a glance.
* To enable "drill-down" analysis into specific product categories.
* To track profitability and identify cost-saving opportunities.

### 🔍 Walkthrough of Key Visuals
* **Executive KPIs:** High-visibility cards showing **Total Sales, Total Profit, and Total Quantity Sold**.
* **Sales Trend (Line Chart):** A temporal analysis showing sales fluctuations over months and years, helping to identify seasonal peaks.
* **Product Category Analysis (Donut/Pie Chart):** Visualizes the contribution of different categories (e.g., Electronics, Clothing) to the total revenue.
* **Regional Performance (Map/Bar Chart):** Highlights top-performing regions and cities, allowing for targeted regional marketing.
* **Profitability by Sub-Category (Waterfall/Bar Chart):** Breaks down which specific items are the most lucrative vs. those with thin margins.
* **Top 5 Customers/Products:** Identifies key drivers of revenue to help in loyalty program management or inventory stocking.

### 💡 Business Impact & Insights
* **Inventory Management:** Spot slow-moving products early to avoid overstocking.
* **Revenue Growth:** Identify high-performing regions to double down on local advertising.
* **Strategic Pricing:** Use profit margin data to adjust pricing strategies on low-margin sub-categories.

## 5. Data Model Schema
The project utilizes a robust Star Schema data model to ensure data integrity and fast calculation speeds.



## 6. Dashboard Preview

![Sales Dashboard Preview](https://github.com/aryaMayank7/Sales-Data-Analysis/blob/main/Sales%20Data%20Analysis%20Dashboard%201.png)
![Sales Dashboard Preview](https://github.com/aryaMayank7/Sales-Data-Analysis/blob/main/Sales%20Data%20Analysis%20Dashboard%202.png)
![Sales Dashboard Preview](https://github.com/aryaMayank7/Sales-Data-Analysis/blob/main/Sales%20Data%20Analysis%20Dashboard%203.png)
![Sales Dashboard Preview](https://github.com/aryaMayank7/Sales-Data-Analysis/blob/main/Sales%20Data%20Analysis%20Dashboard%204.png)
