# 🚀 My First Data Analytics Project: Sales Performance Dashboard

Welcome to my portfolio! This repository marks the beginning of my journey as a Data Analyst. This project features an interactive Power BI dashboard that tracks $127K in total revenue and utilizes relational data modeling to join transaction records with employee attributes.

### 📋 The Problem
Raw transactional sales data lacked organizational context, making it impossible to see which specific employees or regional branches were driving the top revenue.

### 🗂️ Data Modeling & Relationships
To build this dynamic tracking system, I integrated multiple data sources into Power BI and established a relational schema:
* **The Core Data:** Merged SQL transaction databases (`ORDER_SQL`) with an external spreadsheet tracking staff attributes (`employees`).
* **The Relationship:** Created a One-to-Many relationship linking the tables together through the `Employee ID` key to seamlessly connect sales transactions to specific team member profiles.

### 🔍 Key Insights Discovered
* **Volume vs. Value:** Mobile phones sold the highest total volume of units (Count of MONTH), but Cameras generated the absolute highest total overall revenue.
* **Top Market:** Vadodara was the top-performing regional market, followed closely by Surat.
* **Seasonality:** February and March were the clear peak sales months, showing the highest transaction volume.

### 🛠️ Interactive Feature
Added a dynamic **NAME, EMPLOYEE ID** dropdown filter. Because of the established table relationship, managers can instantly filter the entire dashboard to review an individual sales representative's performance.

.
.
.

{HERE IS THE IMAGE}
<img width="1917" height="1018" alt="SALES PERFORMANCE DASHBOARD" src="https://github.com/user-attachments/assets/c20d7bb6-548c-48ac-ae73-b19ba9c70d03" />
