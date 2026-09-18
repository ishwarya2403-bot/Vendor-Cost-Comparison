# Vendor-Cost-Comparison
Excel-based procurement analytics dashboard to compare supplier cost, delivery performance, quantity, and defect rates for data-driven vendor decisions.

# 📊 Vendor Cost Comparison for Procurement Decisions

## 📌 Project Overview

This project is an **Excel-based Procurement Analytics Dashboard** designed to analyze and compare vendor performance across cost, quantity, delivery time, and product quality.

The company purchases products and raw materials from multiple suppliers. Since suppliers differ in pricing, delivery timelines, and quality, a structured data-driven approach is required to compare supplier performance and support procurement decisions.

This project uses Excel to transform procurement data into meaningful KPIs and interactive dashboard insights.

---

## 🎯 Business Problem

Vendor selection decisions can often depend on past relationships or informal experience. Without structured analysis, it can be difficult for management to identify:

* Cost-effective suppliers
* Suppliers with better delivery performance
* Suppliers with lower defect rates
* Differences in supplier pricing
* Overall supplier performance

The objective of this project is to provide a centralized dashboard that helps analyze procurement performance and support data-driven sourcing decisions.

---

## 🎯 Project Objectives

The main objectives of this project are:

* Compare suppliers based on procurement cost
* Analyze supplier pricing
* Measure delivery lead time
* Analyze defective units and defect rates
* Compare purchasing quantities
* Identify supplier performance patterns
* Support supplier negotiation and sourcing decisions
* Provide management with an interactive procurement dashboard

---

## 📂 Dataset

The dataset contains procurement transaction-level information.

### Key Columns

| Column          | Description                               |
| --------------- | ----------------------------------------- |
| Supplier        | Name of the supplier                      |
| Order_Date      | Date when the order was placed            |
| Delivery_Date   | Date when the order was delivered         |
| Item_Category   | Category of the purchased item            |
| Quantity        | Quantity purchased                        |
| Unit_Price      | Price per unit                            |
| Defective_Units | Number of defective units                 |
| Lead Days       | Number of days between order and delivery |
| Total Cost      | Total procurement cost                    |
| Defect Rate     | Percentage of defective units             |

---

## 📊 Key KPIs

The Excel dashboard includes the following key performance indicators:

| KPI                    |         Value |
| ---------------------- | ------------: |
| Number of Suppliers    |             5 |
| Total Quantity         |        89,142 |
| Total Unit Price       |      4,717.38 |
| Average Lead Time      |    11.28 Days |
| Total Procurement Cost | ₹5,396,779.25 |
| Average Defect Rate    |         5.74% |
| Total Defective Units  |         4,862 |

---

## 📈 Dashboard Analysis

The dashboard focuses on multiple areas of procurement performance:

### 💰 Cost Analysis

Analyzes supplier pricing and total procurement cost to understand differences in supplier costs.

### 🚚 Delivery Analysis

Uses **Lead Days** to understand supplier delivery timelines and compare delivery performance.

### 📦 Quantity Analysis

Analyzes purchasing quantities across suppliers and item categories.

### 🔍 Quality Analysis

Uses defective units and defect rate to understand product quality across suppliers.

### 🏢 Supplier Comparison

Provides a structured comparison of suppliers across multiple procurement metrics.

---

## 🛠️ Tools Used

* **Microsoft Excel**
* Pivot Tables
* Pivot Charts
* Excel Formulas
* KPI Cards
* Slicers
* Data Cleaning
* Data Analysis
* Data Visualization

---

## 🔄 Project Workflow

```text
Raw Procurement Data
        ↓
Data Cleaning & Preparation
        ↓
Calculated Fields
        ↓
Pivot Table Analysis
        ↓
KPI Creation
        ↓
Interactive Slicers
        ↓
Charts & Visualizations
        ↓
Excel Procurement Dashboard
        ↓
Business Insights
```

---

## 🧮 Calculated Metrics

### Lead Days

Lead time is calculated using the difference between delivery date and order date:

```text
Lead Days = Delivery Date - Order Date
```

### Total Cost

Total procurement cost is calculated using:

```text
Total Cost = Quantity × Unit Price
```

### Defect Rate

Defect rate is calculated using:

```text
Defect Rate = Defective Units ÷ Quantity
```

---

## 💡 Business Questions

The dashboard helps answer questions such as:

1. Which suppliers are being used by the company?
2. How much quantity has been purchased?
3. What is the total procurement cost?
4. What is the average supplier lead time?
5. How many defective units were received?
6. What is the overall defect rate?
7. How do suppliers differ in pricing?
8. How do suppliers differ in delivery performance?
9. How does supplier quality vary?
10. Which suppliers require further evaluation based on cost, delivery, and quality metrics?

---

## 📌 Key Findings

Based on the dashboard KPI analysis:

* The dataset contains **5 suppliers**.
* Total purchased quantity is **89,142 units**.
* Total procurement cost is approximately **₹53.97 lakh**.
* Average delivery lead time is approximately **11.28 days**.
* Total defective units are **4,862**.
* The overall average defect rate is approximately **5.74%**.

These metrics provide a high-level view of procurement performance and can be further explored using the dashboard's supplier, category, and time-based analysis.

---

## 📊 Dashboard Preview

Add your dashboard screenshot here after uploading it to GitHub.

```markdown
![Procurement Dashboard](images/procurement-dashboard.png)
```

---

## 📁 Project Structure

```text
vendor-cost-comparison-procurement-analysis/
│
├── data/
│   └── procurement_data.xlsx
│
├── dashboard/
│   └── Final Dashboard.xlsx
│
├── images/
│   └── procurement-dashboard.png
│
└── README.md
```

---

## 🎓 Skills Demonstrated

This project demonstrates practical skills in:

* Excel Data Analysis
* Data Cleaning
* Data Preparation
* Pivot Tables
* Pivot Charts
* KPI Development
* Dashboard Creation
* Slicer Implementation
* Procurement Analytics
* Vendor Performance Analysis
* Business Problem Solving
* Data-driven Decision Making

---

## 🚀 Business Value

A structured procurement dashboard can help management move from informal supplier evaluation toward a more consistent, data-based approach.

By comparing **cost, delivery performance, quantity, and quality indicators**, procurement teams can identify areas for supplier negotiation, sourcing optimization, and procurement cost management.

---

## 👩‍💻 Author

**Ishwarya**

Aspiring Data Analyst
**Skills:** Excel | SQL | Python | Power BI | Tableau | Data Analytics

---

## ⭐ Project Category

**Domain:** Procurement / Supply Chain Analytics
**Project Type:** Business Analytics & Dashboard
**Tool:** Microsoft Excel

