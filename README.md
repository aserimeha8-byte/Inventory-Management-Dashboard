# Inventory-Management-Dashboard | Excel, Pivot Table, Power Query, Dashboard making
<img width="551" height="286" alt="image" src="https://github.com/user-attachments/assets/fe848200-f14b-4bcb-b2c3-95c81ebd36a5" />

## 📌 Project Overview
This project focuses on solving real-world inventory management challenges by building an **Excel-based interactive dashboard**.  
The solution follows the **Ask → Prepare → Process → Analyze → Share → Act** analytics framework to transform raw inventory data into actionable business insights.

---

## 1️⃣ ASK – Business Problem & Objective

### 🔴 Problem Statement
Organizations often face **stock-outs, overstocking, and inefficient inventory planning** due to lack of centralized visibility into inventory levels. Manual tracking makes it difficult to identify low-stock risks and excess inventory in time, leading to lost sales and higher holding costs.

### 🎯 Business Objective
To build an **inventory management dashboard** that:
- Tracks real-time inventory levels
- Identifies items below reorder level
- Highlights overstocked products
- Enables faster, data-driven replenishment decisions

### ❓ Key Business Questions
- What is the **total inventory value**?
- How many products are **below the reorder level**?
- Which categories have the **highest low-stock risk**?
- Which items are **overstocked working capital**?
- How does inventory vary by **category and warehouse**?

---

## 2️⃣ PREPARE – Data Collection & Understanding

### 📂 Dataset
- Type: Retail Inventory Data (Simulated)
- Format: Excel (.xlsx)
- Size: ~10,000 records

### 📊 Key Columns
- Product ID
- Product Name
- Category
- Current Stock
- Supplier 
- Warehouse
- Current Stock Price
- Reorder Level
- Unit Cost
- Last/Next Restock Date

The dataset was reviewed to understand business meaning, data types, and relationships before analysis.

---

## 3️⃣ PROCESS – Data Cleaning & Transformation

### 🧹 Data Preparation Steps
- Removed duplicate product records
- Standardized category and warehouse names
- Fixed missing and inconsistent values
- Converted numeric fields to correct formats

### ⚙ Transformations & Calculations
- **Inventory Value = Stock Quantity × Unit Cost**
- **Stock Status**:
  - Below Reorder Level
  - Safe Stock
  - Overstocked
- Automated cleaning steps using **Power Query**

### 🛠 Tools Used
- Microsoft Excel
- Power Query
- IF, SUMIFS, COUNTIFS
- Data validation
- Pivot Chart
- Pivot Table
- Slicers
- Developer Form Control

---

## 4️⃣ ANALYZE – Insights & Metrics

### 📈 KPIs Created
- Total Inventory Value
- Total Number of Products
- Items Below Reorder Level
- Overstocked Items
- Average Reorder Level

### 🔍 Key Analysis
- Category-wise low stock analysis
- Warehouse-wise inventory distribution
- Identification of high-value overstock items
- Risk assessment for stock-outs

---

## 5️⃣ SHARE – Dashboard & Visualization
### 💡 Key Results
- Total Stock Price: $187418229.17
- Total Products: 3000
- Total Category: 5
- Current Stock: 752421
### 📊 Dashboard Features
- KPI cards for quick inventory health check
- Category and warehouse slicers
- Conditional formatting for low-stock alerts
- Pivot charts for trend and distribution analysis

### 🖼 Dashboard Preview
<img width="1100" height="586" alt="Screenshot 2026-01-02 155016" src="https://github.com/user-attachments/assets/4025cc0e-89ab-4add-8a32-bc399384fe93" />


> The dashboard allows stakeholders to quickly identify inventory risks and take immediate action.

---

## 6️⃣ ACT – Business Recommendations & Impact

### 🚀 Actionable Recommendations
- Prioritize replenishment for high-value low-stock products
- Reduce overstock in slow-moving categories
- Reallocate excess inventory across warehouses
- Use the dashboard as a **weekly inventory review tool**

### 📈 Business Impact (Simulated)
- Reduced manual reporting effort by ~40%
- Faster identification of low-stock SKUs
- Improved inventory visibility and control
- Better working capital utilization

---

## 🧠 Skills Demonstrated
- Business problem framing
- Data cleaning & transformation
- Excel formulas & Power Query
- KPI definition and analysis
- Dashboard design & storytelling
- Translating data into business actions


