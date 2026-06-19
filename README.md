# 🚀 My First Data Analytics Project: Sales Performance Dashboard

Welcome to my portfolio! This repository marks the beginning of my journey as a Data Analyst. This project features an interactive dashboard that tracks $127K in total revenue and utilizes relational data modeling to connect transaction records with business dimensions.

### 📋 The Problem
Raw sales logs were completely flat and lacked clear visibility into which specific products, employees, or territories were driving actual business revenue.

### 🗂️ Data Modeling & Relationships
To make the data ready for analysis, I structured a clean relational schema inside the tool by setting up the following relationships:
* **Transactions to Products:** Built a One-to-Many relationship using `Product ID` to accurately map transactions to specific item categories.
* **Transactions to Location:** Linked individual sales entries to regional territories via `City/Region ID`.
* **Transactions to Team:** Connected sales data to employee profiles via `Employee ID` to enable individual performance tracking.

### 🔍 Key Insights Discovered
* **Volume vs. Value:** Mobile phones sold the highest total volume of units, but Cameras generated the highest total overall revenue.
* **Top Market:** Vadodara was the top-performing regional market.
* **Seasonality:** February was the peak sales month.

### 🛠️ Interactive Feature
Added an Employee ID filter leveraging the established relationships so managers can instantly drill down into individual sales team performance.
.
.
.

{HERE IS THE IMAGE}
<img width="1917" height="1018" alt="SALES PERFORMANCE DASHBOARD" src="https://github.com/user-attachments/assets/c20d7bb6-548c-48ac-ae73-b19ba9c70d03" />
