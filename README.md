# KPMG Data Analysis using Excel

## 📌 Project Overview
This project focuses on analyzing customer demographics, transactions, and new customer data to generate actionable business insights. I performed the entire analysis using **Microsoft Excel**, covering data cleaning, segmentation, transaction trends, customer lifetime value (CLV) analysis, and recommendations for improving business performance.

The project is structured into **six key tasks**, each addressing a specific area of analysis, from data preparation to insight generation.

---

## 📂 Dataset
The analysis is based on the **KPMG Dataset**, which includes the following datasets:

### **1. Customer Address Dataset**  
- Provides customer address information and property valuation details.  
- **Key Columns:** `customer_id`, `address`, `postcode`, `state`, `country`, `property_valuation`.

### **2. Customer Demographic Dataset**  
- Contains customer demographic and job-related information along with purchase history.  
- **Key Columns:** `customer_id`, `first_name`, `last_name`, `gender`, `past_3_years_bike_related_purchases`, `DOB`, `job_title`, `job_industry_category`, `wealth_segment`, `owns_car`, `tenure`.

### **3. Transactions Dataset**  
- Includes transaction details such as products purchased, order status, and pricing.  
- **Key Columns:** `transaction_id`, `product_id`, `customer_id`, `transaction_date`, `online_order`, `brand`, `product_line`, `product_class`, `product_size`, `list_price`, `standard_cost`.

### **4. New Customer List Dataset**  
- Contains details of potential new customers and their property valuations.  
- **Key Columns:** `first_name`, `last_name`, `gender`, `past_3_years_bike_related_purchases`, `DOB`, `job_title`, `job_industry_category`, `wealth_segment`, `owns_car`, `address`, `state`, `property_valuation`, `Rank`, `Value`.

---

## 📝 Key Steps Performed

### **1. Data Cleaning**
- Removed duplicate records and standardized state names in the Customer Address dataset.
- Fixed inconsistencies in gender, missing values, and anomalies in Customer Demographics.
- Ensured transaction dates were in a consistent format and removed incomplete records.
- Standardized job titles, address formats, and gender representation in the New Customer List dataset.

---

### **2. Customer Segmentation**
- Segmented customers by **Wealth Segment**, calculating average tenure for each segment.
- Analyzed customer distribution and purchase trends based on **Gender**.
- Segmented customers by **Job Industry** and studied wealth segment distribution within each industry.

---

### **3. Transaction Analysis**
- Created monthly **Sales Trend** charts and identified seasonal patterns and spikes in sales.
- Analyzed **Product Performance** by calculating total sales per brand and average list price by product line.
- Identified **Top 10 Customers** by total transaction value and calculated the average purchases per customer.

---

### **4. New Customer Insights**
- Analyzed the distribution of new customers by **Wealth Segment** and **Job Industry**.
- Visualized **state-wise distribution** of new customers and examined property valuation trends.
- Estimated potential revenue from new customers based on their past purchases and customer value.

---

### **5. Customer Lifetime Value (CLV) Analysis**
- Calculated **CLV** using the formula:  
  `CLV = (Average Purchase Value × Purchase Frequency) × Customer Lifespan`
- Analyzed CLV across wealth segments and demographics such as gender and job industry.

---

### **6. Executive Summary and Recommendations**
- Summarized key insights from segmentation, transaction analysis, new customer analysis, and CLV.
- Recommended **targeted marketing strategies** for high-value customer segments.
- Suggested **business expansion opportunities** based on state-level customer distribution.
- Proposed **improvements in product offerings** by analyzing brand and product line performance.

---

## 📊 Tools & Techniques Used
- **Microsoft Excel**:  
  - Data cleaning (Find & Replace, removing duplicates, handling missing values).  
  - Advanced formulas (VLOOKUP, XLOOKUP, IF, COUNTIF, SUMIF).  
  - Pivot Tables and Pivot Charts for aggregation and visualization.  
  - Conditional Formatting for insights highlighting.  
  - Data visualization (bar charts, line charts, maps, and custom dashboards).

---

## 🎥 Video Explanation
A detailed video walkthrough of the project and analysis process is provided.  
*(Drive link to video is included in the Excel file.)*

---

## 📁 Project Structure
