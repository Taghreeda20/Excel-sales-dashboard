# Excel Sales Dashboard & Analysis

Comprehensive Excel-based tools for interactive sales analysis and business insights using pivot tables, formulas, and visual dashboards.

---

## 📊 Project Overview

This project contains two Excel-based files:

1. **Sales Dashboard** – Visual exploration of sales performance using pivot tables and charts  
2. **Sales Analysis** – Formula-driven analysis answering key business questions

Both files are based on sales data from a bicycle and accessories company.

---

## 🔧 Key Features

### 1. **Dashboard Highlights**
- Interactive dashboard with slicers and charts
- Sales by category (Bikes vs Accessories)
- Monthly trends with running totals
- Regional/territory performance breakdown
- Top-performing products
  
  #### Data Insights
   - Total sales: $125,154,322.06
   - Bikes account for 66.6% of total sales
   - August was the peak sales month
   - Mountain-200 Black (38) was the top selling product with 1,128 orders


### 2. **Formula-Based Sales Analysis**
- Answers 6 specific business questions (see *Questions* sheet)
- Sales line totals including tax and freight
- Category-wise sales summaries
- Order date analysis (extract day, month, year)
- Excel functions demonstrated:
  ```excel
  =SUMIF(G:G,Q8,M:M)           // Total sales by category
  =VLOOKUP(Q15,$D:$G,4,FALSE)  // Product category lookup
  =TEXT(Q25,"DDDD")            // Day name extraction
