# E-Commerce Dashboard – README

## Overview
This Power BI dashboard provides a complete view of an e-commerce business dataset, including sales, orders, profits, product performance, customer regions, and payment insights. The dashboard is interactive, with slicers and cross-filtering across all pages.

---

## Pages & Visuals

### 1. Sales Overview
**Slicers:**  
- Month, Product Category, Payment Mode, City, Region  

**Cards:**  
- Total Sales  
- Total Orders  
- Total Quantity  
- Total Profit  

**Charts:**  
- Total Orders by Category (Clustered Column / Bar)  
- Total Unit Price by Category (Bar)  
- Total Orders by Monthly Trend (Line)  
- Sales Distribution by Category (Pie / Donut)  

**Purpose:** Quick glance of overall sales performance, trends, and distribution.

---

### 2. Payment Insights
**Charts:**  
- Total Revenue by Product Category (Treemap)  
- Total Revenue by Payment Mode (Clustered Column / Bar)  
- Payment Mode vs Profitability (Clustered Column / Bar)  
- Total Revenue by Month (Line)  

**Purpose:** Analyze which payment methods generate more revenue, trends over months, and profitability per payment mode.

---

### 3. Customer, Product & Profitability
**Charts:**  
- Total Revenue by Product Name (Bar / Treemap)  
- Profit Margin by Month (Line / Area)  
- Profit Margin by Product Category (Clustered Column / Bar)  

**Purpose:** Identify top-performing products and profit margins by month and category.

---

### 4. Total Revenue by Location (Optional Map Page)
**Visual:** Bubble Map (City / State)  

**Fields:**  
- Location → City  
- Size → Total Revenue (bubble size)  
- Tooltip → Profit, Total Orders, Quantity  
- Legend → Optional: Category / Payment Mode  

**Design / Formatting:**  
- Bubble colors → Brown gradient (light → dark)  
- Shadow → ON for depth  
- Map background → Transparent  
- Page background → White (#FFFFFF)  

**Purpose:** Analyze total revenue geographically. Can be added as mini map on Sales Overview page or as dedicated page.

---

## Design & Formatting Guidelines
- Consistent theme across all pages  
- Page background → White (#FFFFFF)  
- Colors → Gradient / theme-aligned  
- Shadows / Borders → Subtle for professional look  
- Data Labels → Tooltip preferred for maps  
- Interactivity → Slicers + cross-filtering enabled  

---

## Dataset Fields
- Order ID, Order Date, Customer Name / Email, City, Region, Category, Subcategory, Product Name, Quantity, Unit Price, Discount, Sales, Profit, Payment Mode  

**Note:** Ensure all measures (Total Sales, Total Orders, Total Quantity, Profit Margin) are pre-calculated.

---

## Usage
1. Load the Power BI dataset (.pbix) into Power BI Desktop.  
2. Navigate between pages to explore overall sales, payment insights, and product profitability.  
3. Interact with slicers to filter charts/cards dynamically.  
4. Optional: Explore geographical revenue trends using the Location map page.

---

## Files to Include in Repository
1. Power BI dataset (.pbix)  
2. Source data (.xlsx / .csv)  
3. Screenshots of each page (Sales Overview, Payment Insights, Customer/Product Profitability, Map Page)  
4. README.md (this file)
