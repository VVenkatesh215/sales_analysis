# Sales Analysis

This project presents a Sales Report Dashboard built using Power BI, based on data from two datasets. The objective is to provide meaningful insights into sales distribution across categories, provinces, and over time.

---

## Project Overview

- **Tool Used**: Power BI

- **Key Visualizations**:
  - Sales by Category
  - Sales by Province (Map)
  - Monthly Sales Trend (Line Chart)
  - Monthly KPIs with Year-over-Year (YoY%) Comparison

---

## Data Preparation

Before building the report:
- Incorrect data types in the datasets were identified and converted to appropriate types.
- A relationship was created between the datasets using key fields to enable effective cross-filtering.

---

## Visualizations Explained

### 1. Sales by Category  
A bar chart showing which product categories contribute most to overall sales.

### 2. Sales by Province  
An interactive map highlighting regional sales distribution across various provinces.

### 3. Monthly Sales Trend  
A line chart visualizing monthly sales, capturing fluctuations throughout the year.

### 4. Monthly Sales Table  
A detailed table featuring:
- Monthly sales
- Year-over-Year (YoY) growth percentage
- Year-to-Date (YTD) sales

### 5. KPIs  
- Total Sales Amount  
- Total Quantity Sold

---

## Dataset

- `CustomerMaster.xlsx`: Contains customer-related information and transaction metadata.
- `InvoiceData.txt`: Contains invoice and sales transaction records.

> Sensitive customer details are excluded from the report to maintain privacy.

---

## How to Use

1. Clone this repository.
2. Open `Report.pbit` (or `.pbix`) in Power BI Desktop.
3. Load the data files:
   - Excel file: `CustomerMaster.xlsx`
   - Text file: `InvoiceData.txt`
4. Refresh the dashboard to populate visualizations.
5. To add new records in the future, simply update the datasets (`CustomerMaster.xlsx` and `InvoiceData.txt`) and refresh the report in Power BI — the visuals will update automatically.

---

## Insights

- Peak sales occurred in July and April.
- Negative YoY growth observed in May and August.
- Novelty Shop emerged as the leading sales category.
