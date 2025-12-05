# **Distributed Multi-Source Operational Analytics System**  
### *SQL Server + MySQL + Power BI End-to-End Architecture*

This project delivers a complete **distributed operational analytics pipeline**, integrating **SQL Server**, **MySQL**, and **Power BI** to monitor and analyze inventory behavior across multiple environments.  
It demonstrates how organizations manage **Test vs Production** discrepancies and unify data sources for reliable operational decision-making.

---

## 🚀 **Project Overview**
Modern systems generate data across multiple environments.  
This project shows how to:

- Connect Power BI to **two different databases (SQL Server + MySQL)**
- Perform data cleansing and schema alignment
- Build a **unified dimensional model**
- Create an end-to-end operational monitoring dashboard
- Generate KPIs for stock, variance, and environment comparison

This directly aligns with large-scale distributed data practices used in enterprise and research environments.

---

## 🗂️ **Data Sources**
### **SQL Server**
- Test Environment Inventory Dataset  
- Product Master Dataset  

### **MySQL**
- Production Environment Inventory Dataset  

These were imported into Power BI via native connectors and transformed using Power Query.

---

## 🧩 **Key Features**
### ✔ **Unified Data Model**
Integrated datasets from SQL Server + MySQL into a single analytics framework.

### ✔ **Full ETL Pipeline**
- SQL transformations  
- MySQL transformations  
- Power Query schema merging  
- DAX metric layer  

### ✔ **Operational KPIs**
- Total Stock (Prod + Test)  
- Stock Variance  
- Item Availability %  
- Category-Wise Stock Distribution  
- Environment Comparison Metrics  
- Cost Deviations  

### ✔ **Interactive Power BI Dashboard**
Includes multiple analytical pages featuring:
- KPI cards  
- Variance analysis  
- Environment-level drill-downs  
- Category-wise contributions  
- Time-based insights  

Screenshots are located in `/SCREENSHOTS`.

---



## ⚙️ **Technologies Used**
- **SQL Server 2019**
- **MySQL 8**
- **Power BI Desktop**
- **Power Query (M language)**
- **DAX (Data Analysis Expressions)**
- **ETL Pipeline Techniques**

---



## 📘 **Documentation**
You will find all project documentation in the `/DOCS` folder:

- **requirements.txt**
- **project_summary.md**  
- Architecture diagrams (optional)

---

## 🏁 **Final Deliverables**
This repository contains:

- A fully functional **Power BI operational analytics report**  
- SQL + MySQL integration scripts  
- Clean and reproducible datasets  
- KPI-driven dashboards  
- Documentation suitable for professional and academic portfolios  

---

## ⭐ **How to Use**
1. Clone the repository  
2. Restore SQL Server and MySQL tables using provided scripts  
3. Open the Power BI `.pbix` file  
4. Update the SQL and MySQL connection strings  
5. Refresh the model — all dashboards will populate automatically  


