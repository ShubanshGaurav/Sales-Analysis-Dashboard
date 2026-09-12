# 📊 Sales Analysis Dashboard — Power BI

## 📌 Project Overview

This project is an interactive **Sales Analysis Dashboard built using Microsoft Power BI** to analyse internet sales performance across customers, products, categories, and time.

The dashboard was designed to provide sales managers and sales representatives with a clear view of business performance and help identify top-performing customers and products, monitor sales trends, and compare actual sales against budget.

The project is based on the **Microsoft AdventureWorks sample dataset** and includes supporting data files used to build the Power BI data model.

---

## 🎯 Project Purpose

The main purpose of this project is to transform raw sales data into an interactive business intelligence dashboard that can help answer questions such as:

- How are actual sales performing against the budget?
- Which customers generate the highest sales?
- Which products generate the highest sales?
- How do sales change over time?
- Which product categories contribute the most to overall sales?
- How does sales performance vary across different customer cities?
- Which customers and products should receive greater sales attention?

The dashboard follows the business requirements for providing management-level sales insights as well as detailed customer and product analysis.

---

## 🛠️ Tools & Technologies

| Tool / Technology | Purpose |
|-------------------|---------|
| **Microsoft Power BI** | Dashboard development and data visualization |
| **Power Query** | Data cleaning and transformation |
| **DAX** | Measures, KPIs and analytical calculations |
| **Microsoft Excel** | Budget data |
| **AdventureWorks** | Sample sales database / source data |
| **GitHub** | Project documentation and portfolio hosting |

---

## 📂 Data Source

The primary dataset used in this project is the:

**Microsoft AdventureWorks Sample Data**

The project uses AdventureWorks sales data containing information related to:

- Customers
- Products
- Product Categories
- Sales Transactions
- Calendar / Date information
- Customer locations

Budget information was also incorporated to enable comparison between actual sales and planned sales performance.

Supporting data files are included in this repository for transparency and reproducibility.

---

## 🧩 Data Model

The Power BI report uses a structured data model containing dimension and fact tables.

### Main Data Components

- **Fact Internet Sales** — Contains internet sales transaction information.
- **Customer Dimension** — Contains customer details and customer location information.
- **Product Dimension** — Contains product and product category information.
- **Calendar Dimension** — Provides date-based analysis.
- **Sales Budget** — Contains budget values used for actual vs. budget comparison.

The model allows sales data to be analyzed across multiple business dimensions such as:

**Time → Customer → Product → Category → Location**

---

# 📈 Dashboard Pages

## 1. Sales Overview

The **Sales Overview** page provides a high-level summary of sales performance.

### Key Features

- Total Sales KPI
- Sales vs. Budget KPI
- Budget variance
- Top 10 Customers by Sales
- Top 10 Products by Sales
- Sales by Product Category
- Monthly Sales vs. Budget trend
- Customer City sales map
- Interactive filters

### Key Business Questions

- Are sales above or below budget?
- Which customers contribute the most revenue?
- Which products are performing best?
- How is sales performance changing month by month?
- Which product categories contribute most to total sales?

---

## 2. Customer Details

The **Customer Details** page provides a more detailed view of sales performance by individual customers.

### Key Features

- Customer-level sales analysis
- Monthly sales breakdown
- Top customers by sales
- Customer city visualization
- Customer filtering
- Year and month filtering

This page helps sales representatives identify high-value customers and understand their purchasing patterns.

---

## 3. Product Details

The **Product Details** page focuses on product-level sales performance.

### Key Features

- Product-level sales analysis
- Monthly product sales
- Top 10 products by sales
- Sales by product category
- Product filtering
- Year and month filtering
- Sales vs. budget trend

This view helps identify products with strong sales performance and supports product-level sales follow-up.

---

# 🎛️ Interactive Filters

The dashboard provides interactive filtering capabilities including:

- **Year**
- **Month**
- **Customer City**
- **Sub Category**
- **Category**
- **Product Name**

These filters allow users to drill down from an overall business view into specific customers, products, categories, locations, and time periods.

---

# 📊 Key KPIs & Analysis

The dashboard focuses on the following key performance indicators:

### Sales Performance

- Total Sales
- Total Budget
- Sales vs. Budget
- Budget Variance

### Customer Performance

- Top Customers by Sales
- Customer-level sales trends
- Customer location analysis

### Product Performance

- Top Products by Sales
- Product category contribution
- Monthly product sales

### Time Analysis

- Monthly sales trends
- Actual Sales vs. Budget over time
- Year and month comparison

---

# 💡 Business Insights

The dashboard enables management and sales teams to quickly identify:

- High-performing customers
- High-performing products
- Product categories contributing the most sales
- Monthly sales trends
- Sales performance against budget
- Geographic distribution of customers
- Customers and products that may require additional sales attention

---

# 🏢 Business Use Case

This dashboard was developed around a business requirement for improving sales reporting and providing visual dashboards for sales management.

### Intended Users

**Sales Manager**
- Monitor overall internet sales performance
- Compare sales against budget
- Identify top customers and products
- Track sales trends

**Sales Representative**
- Analyze sales by customer
- Identify high-value customers
- Analyze product-level sales
- Follow up with customers and products with strong sales potential

---

# 📁 Repository Structure

```text
Sales-Analysis-Dashboard/
│
├── 📊 Sales Report Dashboard.PowerBI.pbit
│
├── 📄 README.md
│
├── 📷 Dashboard 1.jpg
├── 📷 Dashboard 2.jpg
├── 📷 Dashboard 3.jpg
│
├── 📂 Data/
│   ├── AdventureWorks Sales Data
│   └── Sales Budget Data
│
└── 📂 Documentation/
    └── Business Requirements
