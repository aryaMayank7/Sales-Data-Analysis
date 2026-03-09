# 📊 Sales Performance & Inventory Insights Dashboard

A comprehensive, interactive Power BI suite designed to track retail performance, analyze promotional effectiveness, and monitor product-level profitability across various Indian cities.

---

## 📝 Short Description / Purpose
The **Sales Performance & Inventory Insights Dashboard** is a multi-page analytical tool built to transform raw transactional data into actionable business intelligence. It allows stakeholders to monitor high-level KPIs, compare period-over-period performance, and drill down into specific product successes or failures. This tool is intended for retail managers and financial analysts to optimize discount strategies and regional sales efforts.

---

## 🛠 Tech Stack
The dashboard was built using the following tools and technologies:

* **📊 Power BI Desktop** – Main data visualization platform used for report creation and canvas design.
* **📂 Power Query** – Used for data cleaning, specifically for handling date formats and merging promotional metadata.
* **🧠 DAX (Data Analysis Expressions)** – Utilized for complex measures like "Net Sales," "Total Profit," and time-intelligence comparisons.
* **📝 Data Modeling** – A Star Schema approach connecting Sales, Products, Customers, and Date tables to enable seamless cross-filtering.
* **📁 File Format** – `.pbix` for development and `.png` for dashboard previews.

---

## 📂 Data Source
* **Source:** Internal Retail Management System (ERP) and Promotional Logs.
* **Structure:** The dataset includes over **3,510 orders** spanning from 2020 to 2024. It tracks 12+ variables including City, Product Category, Discount Value, Net Sales, and Profit margins.

---

## ✨ Features / Highlights

### 1. Business Problem
Retailers often struggle to identify which promotions actually drive profit versus those that only drive volume. Additionally, understanding geographic sales distribution and identifying "bleeding" products (low profit) is difficult without a centralized view.

**Key questions addressed:**
* Which cities are our primary revenue drivers?
* Are high discounts in "Weekend Flash Sales" translating to sustainable profit?
* Which products are high-volume but low-margin?

### 2. Goal of the Dashboard
* To provide a **geospatial view** of sales across India.
* To evaluate the **ROI of different promotion categories**.
* To enable **comparative analysis** between two custom date ranges.
* To identify the **Top and Bottom 5 performers** across Sales, Quantity, and Profit.

### 3. Walkthrough of Key Visuals
* **Sales by City (Map):** A bubble map showing heavy sales concentration in northern and western India (Delhi, Ahmedabad, Mumbai).
* **Average Discount by Promotion:** A bar chart revealing that "Weekend Flash Sales" carry the highest discount burden (22.6K), while "Festive Diwali" remains conservative.
* **Relationship between Profit and Sales (Scatter Plot):** Shows a strong linear correlation, indicating stable margins across most transactions.
* **Top/Bottom 5 Product Analysis:**
    * **Top Performer:** Apple iPhone 14 (leading in Sales, Quantity, and Profit).
    * **Underperformer:** Colgate Toothpaste (lowest sales/profit contribution).
* **Comparative Analysis Page:** Side-by-side bar charts allowing users to compare "Sales 1 vs Sales 2" across different time buckets.
* **Granular Transaction Table:** A detailed list view showing individual Order IDs, Discount Percentages, and Net Sales for auditing.

### 4. Business Impact & Insights
* **Inventory Optimization:** High-volume/low-profit items (like certain toiletries) can be identified for potential price restructuring.
* **Regional Strategy:** Data suggests a strong market presence in Bhopal and Indore; marketing spend could be shifted to lower-performing bubbles like Chennai to balance growth.
* **Promotion Rationalization:** By comparing "Weekend Flash Sale" discounts against the Net Sales trend, management can decide if the 22.6K average discount is generating a sufficient sales spike.

---

## Data Model Schema
The project utilizes a robust Star Schema data model to ensure data integrity and fast calculation speeds.

---

## Dashboard Preview

![Sales Dashboard Preview](https://github.com/aryaMayank7/Sales-Data-Analysis/blob/main/Sales%20Data%20Analysis%20Dashboard%201.png)
![Sales Dashboard Preview](https://github.com/aryaMayank7/Sales-Data-Analysis/blob/main/Sales%20Data%20Analysis%20Dashboard%202.png)
![Sales Dashboard Preview](https://github.com/aryaMayank7/Sales-Data-Analysis/blob/main/Sales%20Data%20Analysis%20Dashboard%203.png)
![Sales Dashboard Preview](https://github.com/aryaMayank7/Sales-Data-Analysis/blob/main/Sales%20Data%20Analysis%20Dashboard%204.png)
