
# 🌍 Global Retail Sales & Customer Analysis | Power BI

An interactive **Power BI Business Intelligence project** focused on analysing global retail sales, profitability, customer behaviour and regional business performance.

The project explores different aspects of retail operations, including sales trends, profit performance, product categories, customer segments, geographical markets and valuable customers.

The objective is to transform raw retail sales data into meaningful business insights that support strategic decision-making, sales optimisation and profitability analysis.

## 🎯 Project Objectives

- Analyse overall sales and profit performance.
- Identify sales trends across different years.
- Compare sales and profit across product categories.
- Analyse customer segments and purchasing behaviour.
- Identify top-performing countries and regions.
- Identify the most active and valuable customers.
- Evaluate regional sales and profitability performance.
- Monitor year-over-year sales and profit growth.

## 📂 Dataset Overview

- **Dataset:** Global Retail Sales Dataset.
- **Source File:** `global_retail_sales_data.xlsx`.
- **Dataset Type:** Global retail transaction-level dataset.
- **Total Records:** 51,290.
- **Total Columns:** 23 (Orders sheet).
- **Unique Orders:** 25,035.
- **Unique Customers:** 1,590.
- **Countries Covered:** 147.
- **Time Period:** 2011–2014.

The dataset contains seven Excel worksheets:

- `product_data` – Product information and categories.
- `location_data` – City, state, country, market and region details.
- `customer_data` – Customer names and segments.
- `sales_data` – Transaction-level sales information.
- `Orders` – Consolidated order, customer, product and sales information.
- `Returns` – Returned order information.
- `People` – Regional manager information.

**Key Dataset Attributes:**

- Order ID
- Order Date
- Ship Date
- Ship Mode
- Customer ID
- Customer Name
- Segment
- Country
- Market
- Region
- Product Category
- Sub-Category
- Sales
- Quantity
- Discount
- Profit
- Shipping Cost
- Order Priority

## 🛠️ Tools & Technologies

- **Power BI Desktop** – Data modelling, DAX and interactive dashboard development.
- **Power Query** – Data cleaning and transformation.
- **DAX** – Measures, calculations and KPI development.
- **Excel** – Source dataset management.

## 🔄 Data Cleaning & Transformation

- Imported the Excel dataset into Power BI.
- Reviewed all seven worksheets and their structures.
- Checked column names and data types.
- Checked missing values and duplicate records.
- Corrected data types for numerical, categorical and date columns.
- Reviewed sales, profit, quantity and discount fields.
- Prepared customer, product and geographical information for analysis.
- Organised the data for interactive reporting.
- Prepared calculated measures for sales and profit analysis.

## 🏗️ Data Modelling

The project uses multiple data tables to organise retail business information.

**Main Data Table**

- `Orders` – Contains order details, customer information, geographical details, product information, sales, quantity, discount and profit.

**Supporting Tables**

- `product_data` – Product details and product categories.
- `location_data` – Geographical and market information.
- `customer_data` – Customer details and segments.
- `sales_data` – Transaction-level sales information.
- `Returns` – Returned order details.
- `People` – Regional manager information.

Power BI report calculations and visualisations are used to analyse sales, profitability and customer performance.

## 📊 Key DAX Measures & KPIs

**Sales Analysis**

- Total Sales
- Total Sales Last Year
- Year-over-Year Sales Growth
- Average Sales Per Order

**Profit Analysis**

- Total Profit
- Total Profit Last Year
- Year-over-Year Profit Growth
- Average Profit Per Order

**Customer Analysis**

- Total Orders
- Total Products
- Active Buyers
- Valuable Customers
- Average Sales Per State

Advanced Power BI features:

`CALCULATE()` · `SUM()` · `AVERAGE()` · `DIVIDE()` · `DISTINCTCOUNT()` · `FILTER()` · `Time Intelligence` · `Field Parameters`

## 📈 Power BI Dashboard Pages

### 1. Sales Analysis Dashboard

Provides an overview of global retail sales performance.

**Key KPIs:**

- Total Sales
- Total Sales Last Year
- Year-over-Year Growth
- Average Sales Per Order

**Visualisations:**

- Total Sales Comparison
- Total Sales by Top Countries
- Total Sales by Category
- Total Sales by Customer Segment
- Total Sales by Year
- Interactive slicers and filters

### 2. Profit Analysis Dashboard

Focuses on analysing profitability across different business dimensions.

**Key KPIs:**

- Total Profit
- Total Profit Last Year
- Year-over-Year Profit Growth
- Average Profit Per Order

**Visualisations:**

- Total Profit Comparison
- Total Profit by Category
- Total Profit by Customer Segment
- Total Profit by Top Countries
- Interactive slicers and filters

### 3. Customer & Demographics Dashboard

Provides insights into customer activity, customer value and geographical performance.

**Key Analysis Areas:**

- Top 10 Active Buyers
- Top 10 Valuable Customers
- Top 3 Valuable States
- Total Orders
- Total Products
- Average Sales Per State
- Profit by Customer Segment
- Sales and Profit by Region

**Visualisations:**

- Clustered Bar Charts
- Clustered Column Charts
- Donut Charts
- Regional Sales and Profit Analysis
- Interactive slicers

## 💡 Key Business Insights

| KPI | Result |
|---|---:|
| Total Sales | 12.64 Million |
| Total Profit | 1.47 Million |
| Total Orders | 25,035 |
| Total Quantity Sold | 178,312 |
| Total Customers | 1,590 |
| Countries Covered | 147 |
| Average Sales Per Order | 504.99 |

**Additional Business Insights:**

- Technology generated the highest sales among the three product categories, contributing approximately 4.74 million.
- Office Supplies generated approximately 518.47K in profit.
- Consumer customers contributed the highest sales, approximately 6.51 million.
- The United States recorded the highest sales among countries, contributing approximately 2.30 million.
- Sales increased consistently from 2011 to 2014.
- Total sales reached approximately 4.30 million in 2014.
- Customer segmentation helps identify valuable customers and understand purchasing behaviour.

*Note: Business insights are calculated from the supplied dataset. Values are rounded for presentation.*

## 🎛️ Power BI Features

- Interactive KPI cards.
- Sales and profit performance analysis.
- Year-over-year growth analysis.
- Customer segmentation.
- Top customer analysis.
- Geographical sales analysis.
- Product category performance comparison.
- Regional profitability analysis.
- Interactive slicers and filters.
- Multiple Power BI visualisations.

## 📁 Project Structure

```text
Global-Retail-Sales-Analysis/
│
├── Dataset/
│   └── global_retail_sales_data.xlsx
│
├── PowerBI/
│   └── customer.pbix
│
└── README.md
```

## 🚀 How to Use This Project

1. Clone or download this GitHub repository.
2. Open the `PowerBI` folder.
3. Open `customer.pbix` using Power BI Desktop.
4. Update the Excel source file path if required.
5. Refresh the dataset.
6. Explore the Sales, Profit and Customer dashboards.
7. Use interactive filters and slicers to analyse business performance.

## 👨‍💻 Author

**Devaprakash**

B.Tech Graduate in Artificial Intelligence and Data Science

Aspiring Data Analyst | Power BI | SQL | Python | Excel

---

⭐ If you find this project useful, consider giving this repository a star!

# E-commerce-Analysis-Dashboard
