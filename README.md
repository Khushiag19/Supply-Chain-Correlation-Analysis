# Supply Chain Correlation Analysis – OptimalFlow Logistics

This repository contains a correlation analysis and visualization of key supply chain performance metrics for an automotive manufacturer. The analysis was performed using Microsoft Excel following best practices from the **Visualizing Forecasts with Excel** module.

---

## 📘 Business Context

**OptimalFlow Logistics** is a supply chain consulting firm helping manufacturers optimize procurement and inventory management.  
The objective of this analysis is to identify relationships between critical supply chain variables to improve:
- Supplier selection  
- Inventory planning  
- Cost optimization  

Dataset includes **60 procurement transactions** across the following key metrics:
- `Supplier_Lead_Time` — Days from order placement to delivery  
- `Inventory_Levels` — Current stock quantities (units)  
- `Order_Frequency` — Number of orders placed per month  
- `Delivery_Performance` — On-time delivery rate (%)  
- `Cost_Per_Unit` — Unit cost in dollars ($)

---

## 🧮 Methodology

### 1. Correlation Matrix Creation
- Opened dataset in Excel  
- Enabled **Data Analysis ToolPak**  
  - File → Options → Add-ins → Analysis ToolPak  
- Generated correlation matrix using:
- Selected all 5 data columns, with “Labels in first row” checked  
- Output directed to a new worksheet

### 2. Excel Heatmap Formatting
- Selected correlation matrix values (excluding labels)
- Applied conditional formatting:
- **Red:** Low correlation  
- **White:** Neutral correlation  
- **Green:** High correlation

### 3. Output Files
The following files were exported and are included in this repository:
| File Name | Description |
|------------|-------------|
| `correlation.csv` | Correlation matrix values (numeric) |
| `heatmap.png` | Screenshot of Excel conditional formatting (Red–White–Green palette) |
| `README.md` | Documentation of methodology and context |

---

## 📊 Results Overview

The correlation analysis reveals the interdependencies among supplier performance indicators.  
Notably:
- **Supplier Lead Time** shows a negative relationship with **Delivery Performance**, implying longer lead times reduce on-time delivery rates.
- **Cost Per Unit** tends to correlate positively with **Lead Time**, indicating faster suppliers may charge a premium.

---

## 📂 Repository Structure

📁 Supply-Chain-Correlation-Analysis
│
├── correlation.csv # Correlation matrix data
├── heatmap.png # Correlation heatmap visualization
└── README.md # Project documentation

---

## 📧 Contact

Prepared by **Khushi Agarwal**  
Email: **23f3001513@ds.study.iitm.ac.in**

---

## 📈 Tools Used
- Microsoft Excel (Data Analysis ToolPak)
- Python (for automated validation and visualization)
- GitHub (for repository hosting)

---


