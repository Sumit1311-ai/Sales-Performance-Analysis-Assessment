# Sales Performance Analysis

## 📊 Project Overview

This project is an end-to-end Sales Performance Analysis project built using Python, Pandas, Exploratory Data Analysis (EDA), and Microsoft Power BI.

The objective of this project is to transform raw sales data into a clean, reliable dataset and create an interactive dashboard to analyze sales, profit, customers, orders, products, regions, and sales trends.

---

## 🔄 Project Workflow

Raw Data  
↓  
Python / Pandas Data Cleaning  
↓  
Data Validation  
↓  
Exploratory Data Analysis (EDA)  
↓  
Cleaned Dataset  
↓  
Power BI Data Transformation & DAX  
↓  
Interactive Sales Performance Dashboard

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- Jupyter Notebook / Google Colab
- Exploratory Data Analysis (EDA)
- Microsoft Power BI
- DAX
- CSV

---

## 📁 Dataset

The dataset contains sales transaction records with information related to:

- Order ID
- Order Date
- Customer ID
- Region
- City
- Category
- Product
- Sales Channel
- Customer Type
- Quantity
- Unit Price
- Discount
- Sales Amount
- Profit
- Payment Method

The raw dataset contains more than 10,000 records before data cleaning.

---

## 🧹 Data Cleaning

The raw dataset was cleaned and prepared using Python and Pandas.

### Cleaning steps included:

- Handling missing values
- Converting columns to appropriate data types
- Standardizing text values
- Removing invalid quantity records
- Investigating and handling suspicious price outliers
- Removing duplicate records
- Converting Order Date into a proper datetime format
- Validating numeric columns
- Performing final data quality checks

### Final Dataset Validation

After cleaning:

- **9,978 valid records**
- **0 missing values**
- **0 duplicate records**
- **0 invalid quantity records**
- **0 invalid sales records**
- **0 invalid profit records**

---

## 📈 Exploratory Data Analysis

EDA was performed using Python and Pandas to understand the major business patterns in the dataset.

The analysis covered:

- Overall sales and profit performance
- Sales by category
- Sales by region
- Sales by city
- Sales by product
- Monthly sales and profit trends
- Sales channel performance
- Customer type analysis
- Discount and profit margin analysis

---

## 📊 Power BI Dashboard

An interactive **Sales Performance Dashboard** was created using Microsoft Power BI.

### Dashboard KPIs

- Total Sales: **₹283.77M**
- Total Profit: **₹98.67M**
- Total Orders: **9.98K**
- Total Customers: **9.44K**
- Total Quantity: **28.93K**
- Average Order Value: **₹28.44K**

### Dashboard Visuals

- Sales by Region
- Monthly Sales & Profit Trend
- Sales by Product
- Sales by Category
- KPI Cards
- Interactive Filters / Slicers

### Interactive Filters

The dashboard includes slicers for:

- Category
- Region
- Order Date
- Sales Channel

Users can interact with these filters to dynamically analyze different segments of the sales data.

---

## 💡 Key Insights

The analysis provides visibility into:

- Regional sales performance
- Product-level sales contribution
- Category-wise sales distribution
- Monthly sales and profit trends
- Customer and order performance
- Impact of discounts on profitability
- Comparison between different sales channels

---

## 📂 Repository Structure

```text
Sales-Performance-Analysis-Assessment/
│
├── data/
│   ├── raw_sales_assessment_10000x15.csv
│   └── cleaned_sales_data.csv
│
├── Assessment.ipynb
│
├── Sales_Performance_Analysis.pbix
│
└── README.md
