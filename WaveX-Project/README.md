# Power BI Business Dashboards – HR & Sales

## 📊 Overview
This repository showcases two end-to-end **Power BI dashboards (HR & Sales)** built with proper **data cleaning, transformation, and star schema modeling** to deliver reliable, decision-ready insights for business stakeholders.

The project demonstrates real-world Power BI development practices including ETL, data modeling, DAX, and interactive reporting.

---

## 🧑‍💼 HR Dashboard

### 🎯 Objective
To analyze employee demographics, satisfaction, promotion status, and workforce distribution to support HR strategy and workforce planning.

### 🔑 Key Metrics
- Total Employees  
- Average Job Satisfaction  
- Promotion Due vs Not Due  
- Employee Distance (Near vs Far)  
- Gender Distribution  

### 📈 Visual Insights
- Average Age by Department  
- Employees by Gender  
- Employees by Education Level  
- Job Satisfaction by Years of Experience  
- Top Job Grades by Distance  
- Promotion Eligibility Analysis  

### 🛠 Key Use Cases
- Identify departments with an aging workforce  
- Track promotion readiness  
- Monitor employee satisfaction trends  
- Understand workforce distribution by location  

---

## 💰 Sales Dashboard

### 🎯 Objective
To monitor overall sales performance, profitability, payment behavior, distributor contribution, and growth trends.

### 🔑 Key Metrics
- Total Sales  
- Quantity Sold  
- Total Profit  
- Average Profit per Unit  

### 📈 Visual Insights
- Sales by Product Category  
- Sales by Payment Method  
- Top Distributors by Revenue  
- Sales Trend & Forecast  
- Quarter-wise Sales Growth  

### 🛠 Key Use Cases
- Identify high-performing product categories  
- Analyze customer payment preferences  
- Track distributor performance  
- Monitor seasonal and quarterly sales growth  

---

## 🧹 Data Cleaning & Transformation
- Removed duplicates and invalid records  
- Standardized categorical values  
- Handled missing values  
- Created derived columns for analysis  
- Optimized data types for performance  

All transformations were implemented using **Power Query (ETL)**.

---

## 🧩 Data Modeling – Star Schema

The Sales dashboard follows a **Star Schema** design for performance and scalability.

### 🟡 Fact Table
- **Sales**
  - OrderID
  - Date
  - DistributorID
  - Payment Method
  - Cost Per Unit
  - Payment Status

### 🔵 Dimension Tables
- **Product**
  - Product ID
  - Product Name
- **Category**
  - Category Type
  - Product ID
- **Distribution**
  - City
  - Country
  - Distributor Email

### ⭐ Benefits of Star Schema
- Faster report performance  
- Simplified DAX calculations  
- Clear separation of facts and dimensions  
- Scalable for future data growth  

---

## 🛠 Tools & Technologies Used
- **Power BI Desktop**
- **Power Query (ETL)**
- **DAX Measures**
- Star Schema Data Modeling
- Interactive slicers & drill-downs

---

## 🚀 How to Use
1. Download the `project.pbix` file  
2. Open in **Power BI Desktop**  
3. Refresh data (if source available)  
4. Publish to **Power BI Service** for sharing  

---

## 🖱️ Dashboard Previews

### 🔷 Sales Dashboard
[![View Sales Dashboard](https://img.shields.io/badge/View-Sales%20Dashboard-blue?style=for-the-badge)](https://github.com/kalpana-da/Power-BI-Projects/blob/main/WaveX-Project/img/sales_dashboard.png)

---

### 🟣 HR Dashboard
[![View HR Dashboard](https://img.shields.io/badge/View-HR%20Dashboard-purple?style=for-the-badge)](https://github.com/kalpana-da/Power-BI-Projects/blob/main/WaveX-Project/img/HR_Dashboard.png)

---

## 📌 Intended Audience
- Business Analysts  
- HR Managers  
- Sales Managers  
- Data Analytics Learners  
- Power BI Developers  

---

## 📄 License
This project is created for **learning, portfolio, and demonstration purposes**.

---

## 🙌 Author
**Kalpana S**  
Data Analytics & Power BI Developer  

🔗 LinkedIn: https://www.linkedin.com/in/skalpana/  
🔗 GitHub: https://github.com/kalpana-da   
