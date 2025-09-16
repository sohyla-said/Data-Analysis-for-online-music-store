# 🎵 Music Store Sales Analysis

This project analyzes sales data from a small online music store. 
The goal is to generate quick insights for marketing and product decisions, focusing on customer behavior, revenue trends, and top-performing products.

---

## 📌 Objectives

The analysis aims to answer the following key business questions:

1. **Which country has the most customers?**  
2. **Which customer has spent the most money?**  
3. **How much revenue was generated from each music genre?**  
4. **What is the average transaction value per customer?**  
5. **What is the total revenue for each year?**

---

## 🗂 Dataset

- Source: [Music Store Dataset](https://github.com/rishabhnmishra/SQL_Music_Store_Analysis/blob/main/music%20store%20data.zip)  
- Format: CSV files with main tables:  
  - **customer** – customer details (name, country, contact info)  
  - **invoice** – invoice-level data (date, billing country, total amount)  
  - **invoice_line** – purchased items per invoice (unit price, quantity, track ID)  

---

## 🛠 Project Workflow

### **Task 1: Data Ingestion & Initial Exploration**
- Read the CSV files int pandas dataframes.
- Inspected available tables (`customers`, `invoices`, `invoice_items`, `tracks`, `genres`).  
- Previewed data to understand schema and relationships.

### **Task 2: Data Cleaning & Preprocessing** 
- Checked for missing or duplicate values.  
- Standardized column names for easier querying.  

### **Task 3: Data Integration & Aggregation**
- Joined tables to combine customer, invoice, and product information.  
- Aggregated data to calculate revenue, customer spend, and transaction metrics.  

### **Task 4: Insight Generation & Reporting**
- Identified top countries by customer count.  
- Found highest-spending customer.  
- Calculated revenue contribution per music genre.  
- Computed average transaction value per customer.  
- Summarized yearly revenue trends.  

---

## 📊 Key Insights

- **Top Country by Customers:** 🇺🇸 United States (highest number of customers).  
- **Top Spending Customer:** Identified by total purchases across invoices.  
- **Revenue by Genre:** Rock and Metal dominate revenue share.  
- **Average Transaction Value:** Indicates typical customer spending behavior.  
- **Yearly Revenue Trends:** Useful for detecting growth or seasonal performance.  

*(Exact values and charts can be found in the notebook.)*

---

