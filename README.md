
# 📊 Marketing Campaign & Customer Analysis Dashboard

## 🎯 Project Overview

This project provides a comprehensive analysis of **marketing performance** and **customer behavior** using campaign and customer datasets.  
The objective is to evaluate advertising effectiveness, customer segmentation, and sales performance through data modeling and visualization.  
The final output is an **interactive Power BI dashboard** that delivers actionable insights for strategic marketing decisions.

---

## 🔍 Steps Taken

### 1. Data Source

**Datasets**
- *Marketing Campaign Data* – Campaign performance, clicks, conversions, impressions, and sales.  
- *Customer Data* – Customer demographics, gender, age, and location.  
- **Format:** Excel files (from Kaggle).

---

### 2. Data Cleaning & Preparation

- Removed duplicates and handled missing values.  
- Standardized field names and data formats (dates, numeric fields, and text).  
- Derived new columns such as **Age Range**, **Customer Segment**, and **Profit**.  
- Verified data integrity across campaign and customer records.

---

### 3. Data Modeling in Power BI

- Imported cleaned datasets into **Power BI**.  
- Created relationships among key tables:
  - `Customer[Customer ID]` → `Campaign`
  - `DateTable[Date]` `
- Defined *one-to-many* and *many-to-one* relationships.  
- Added a `DateTable` to support **time intelligence** functions and trend analysis.

---

## 🧮 Calculated Measures (DAX)

Below are key **DAX measures** used in the dashboard:

| **Measure** | **Description** |
|--------------|----------------|
| `Total Sales = SUM(Customer[Sales])` | Aggregates total sales from all campaigns or customers. |
| `Total Spending = SUM(Customer[Total Spending])` | Calculates overall marketing ad spend. |
| `Total Impressions = SUM(Customer[Impressions])` | Computes total ad impressions. |
| `Total Clicks = SUM(Customer[Clicks])` | Measures total clicks received from ads. |
| `Total Conversions = SUM(Customer[Conversions])` | Counts successful conversions. |
| `Profit = [Total Sales] - [Total Spending]` | Calculates net profit. |

---

## 📈 Analysis & Key Metrics

### **Marketing Campaign KPIs**
- Campaigns: **200**  
- Clicks: **25M**  
- Conversions: **3M**  
- Impressions: **357M**  
- Sales: **734M**  
- Total Spending: **639K**

### **Customer Insights**
- Customers: **100**  
- Age Range: **19 – 65 years**  
- Top Segment: **Regular (0.30B Sales)**  
- Gender Sales Distribution: **Female 38.55%, Male 35.51%, Other 25.93%**  
- Most Profitable Location: **Chicago**

---

## 📊 Dashboard Overview

### **A. Marketing Campaign Dashboard**
- KPIs for campaign performance (Clicks, Conversions, Impressions, Sales).  
- Trend lines for clicks, impressions, and conversions by month.  
- Monthly Ad Spend vs. Sales comparison.  
- Donut chart visualizing clicks, conversions, and impressions.

### **B. Customer Analysis Dashboard**
- Segmentation by customer type (Regular, Premium, New).  
- Sales by age group and gender.  
- Profit by customer segment.  
- Location-based summary of sales, spending, and profit.

---

## 🛠 Tools & Technologies

- **Power BI Desktop** – Data modeling, DAX calculations, and dashboard creation.  
- **Microsoft Excel** – Data pre-cleaning and transformation.  
- **DAX (Data Analysis Expressions)** – Custom calculations and KPIs.  
- **Kaggle** – Data source for marketing and customer data.


---

## 📘 Key Learnings

- Advanced **data modeling** and **DAX measure** development.  
- Integration of marketing and customer datasets for unified analysis.  
- **Visual storytelling** with KPIs, charts, and demographics.  
- Designing interactive dashboards to support marketing and business decisions.

---

