# 📦 E-Commerce Customer Behavior & Sales Analysis  
### Tableau Portfolio Project | Kaggle Dataset | Business Analytics

---

## 📌 1. Problem Statement  
This project analyzes e-commerce customer behavior to help a retail business understand:

- Which customer segments drive the most revenue  
- Which product categories perform the best  
- How discounts and delivery times influence customer satisfaction  
- How age, gender, and city demographics affect purchasing patterns  
- What sales trends occur over time  

The goal is to provide actionable insights to improve **marketing**, **pricing**, **inventory planning**, and **overall customer experience**.

---

## 📊 2. Data Source & Description  

**Dataset Source:**  
Kaggle - *E-Commerce Customer Behavior and Sales Analysis (Turkey)*  
https://www.kaggle.com/datasets/umuttuygurr/e-commerce-customer-behavior-and-sales-analysis-tr

**Dataset Size:** 5,000 transactions from January 2023 to March 2024.

### **Customer Data**
- `CustomerID` - Unique customer identifier  
- `Gender`  
- `Age`  
- `Age_Group` - 18-28, 29-44, 45-60, 61-75  
- `City`  

### **Order Data**
- `OrderID`  
- `Order_Date`  
- `Quantity`  
- `Price` (per unit)  
- `Discount_Applied`  
- `Payment_Method`  

### **Product Data**
- `Category` - Electronics, Fashion, Sports, Beauty, Books, Home & Garden, Toys  
- `Rating` - Customer rating (1-5)  
- `Delivery_Time` - Days until delivery  

These fields support analysis of sales performance, customer segmentation, product trends, and customer satisfaction.

---

## 📈 3. Model Outputs: Tableau Dashboards & Key Insights  

This project includes **three Tableau dashboards**: Sales, Customer, and Product.  
Below is a summary of the insights produced from the visualizations.

---

### ⭐ A. Sales Dashboard  
**Key Insights**
- **Total Sales:** $5.04M  
- **Total Orders:** 5,000  
- **Electronics is the highest-revenue category (≈47% of total sales)**  
- Revenue spikes around **July 2023** and **February 2024**  
- Top-performing cities: **Istanbul, Ankara, Izmir**

**Business Impact**
- Electronics inventory and promotions should be prioritized  
- City-specific marketing strategies could increase sales in major metro areas  

---

### ⭐ B. Customer Dashboard  
**Key Insights**
- Gender split is balanced, with **female customers spending slightly more overall**  
- **Age 29-44** produces the highest total sales  
- Electronics is the preferred category across all age groups  
- Top customers individually spent **over $21,000+**

**Business Impact**
- Marketing resources should target the 29-44 age group  
- Tailored promotions may improve engagement for gender-specific categories  

---

### ⭐ C. Product Dashboard  
**Key Insights**
- **Net Sales:** $4.9M  
- **Average Customer Rating:** 3.9  
- Medium discounts (10-20%) result in **higher ratings**  
- Heavy discounts correlate with **lower customer satisfaction**  
- Slow delivery times (>20 days) reduce ratings from ~4.0 to ~3.0  
- Electronics remains profitable across most cities  

**Business Impact**
- Implement moderate discount strategies  
- Improving delivery logistics can significantly boost customer satisfaction  
- Electronics should remain a priority product category  

---

## ⚠️ 4. Limitations  

### **Dataset Limitations**
- 5,000 rows are relatively small for predictive modeling  
- Data reflects only Turkish e-commerce customers  
- No profit margin, return/refund, or shipping cost information  
- Ratings are subjective and may not fully represent satisfaction  

### **Dashboard Limitations**
- Time-series analysis limited to a ~14-month window  
- No direct CLV (Customer Lifetime Value) fields  
- Profit inferred through behavior patterns, not exact values  

---

## ✅ 5. Were We Able to Solve the Problem?  
**Yes.**  
The dashboards successfully answered all core business questions:

- Identified top revenue-driving customer segments  
- Highlighted best-performing and discount-sensitive product categories  
- Quantified the impact of discounts and delivery time on customer satisfaction  
- Revealed demographic buying behavior  
- Provided seasonal and monthly sales insights  

The analysis provides clear, actionable recommendations for improving marketing strategy, inventory decisions, pricing, and customer experience.

---

## 🧠 6. Skills Demonstrated  
- Tableau (KPIs, tree maps, heatmaps, line charts, LOD calculations)  
- Data analysis & wrangling  
- Dashboard design & visualization  
- Business analytics  
- Customer segmentation  
- Sales & product analysis  
- Storytelling with data  


