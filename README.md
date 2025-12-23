# 🛒 Retail-Customer-Purchase-Behavior-Analysis
### End-to-End Data Analytics Project

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-003B57?style=for-the-badge&logo=databricks&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

---

## 📌 Project Overview
This project analyzes **customer shopping behavior** using transactional retail data to extract **actionable business insights**.  
The goal is to understand spending patterns, customer segments, product performance, discount impact, and subscription behavior to support **data-driven decision-making**.

The project demonstrates a **full analytics lifecycle**:
- Data preprocessing and feature engineering in **Python**
- Business-focused querying using **SQL (PostgreSQL)**
- Interactive visualization and storytelling with **Power BI**

---

## 📊 Dataset Summary
- **Total Records:** 3,900 transactions  
- **Total Features:** 18  

### Key Attributes
- **Customer Demographics:** Age, Gender, Location, Subscription Status  
- **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color  
- **Behavioral Metrics:** Discount Applied, Promo Code Usage, Purchase Frequency, Review Ratings, Shipping Type  

Missing values in the *Review Rating* column were handled using **category-wise median imputation**.

---

## 🧰 Tech Stack Used
| Layer | Tools |
|-----|------|
| Data Cleaning & EDA | Python (Pandas, NumPy) |
| Database | PostgreSQL |
| Querying | SQL |
| Visualization | Power BI |
| Documentation | Markdown |

---

## 🔄 Project Workflow

### 1️⃣ Data Preparation & Cleaning (Python)
- Loaded dataset using Pandas
- Explored structure using `.info()` and `.describe()`
- Handled missing values using median imputation
- Standardized column names to snake_case
- Performed feature engineering:
  - `age_group`
  - `purchase_frequency_days`
- Removed redundant features
- Loaded cleaned data into PostgreSQL for analysis

---

### 2️⃣ Business Analysis Using SQL
Key business questions answered:
- Revenue contribution by gender
- High-spending customers who used discounts
- Top 5 products by average rating
- Shipping type vs average spend
- Subscriber vs non-subscriber revenue
- Discount-dependent products
- Customer segmentation (New, Returning, Loyal)
- Top products per category
- Repeat buyers vs subscription likelihood
- Revenue contribution by age group

This stage highlights **joins, aggregations, filtering, grouping, and window functions**.

---

### 3️⃣ Interactive Dashboard (Power BI)
An interactive Power BI dashboard was created to visualize:
- Total customers & average purchase amount
- Revenue by category and age group
- Subscription distribution
- Discount usage trends
- Customer segmentation

The dashboard enables **executive-level insights** through slicers and filters.

---

## 💡 Key Insights
- Male customers contribute higher overall revenue
- Loyal customers form the largest segment
- Express shipping users have slightly higher average spend
- Some products rely heavily on discounts
- Young adults generate the highest revenue share

---

## 📌 Business Recommendations
- Promote exclusive benefits to boost subscriptions
- Strengthen loyalty programs for repeat customers
- Optimize discount strategies to protect margins
- Highlight top-rated products in campaigns
- Focus marketing on high-revenue age groups

---

## 🎯 Skills Demonstrated
- Data Cleaning & Feature Engineering  
- Exploratory Data Analysis (EDA)  
- SQL-Based Business Analytics  
- Customer Segmentation  
- Dashboarding & Data Storytelling  
- End-to-End Analytics Pipeline  

---

## 🚀 Why This Project Stands Out
- Real-world retail use case  
- Strong Python + SQL integration  
- Business-focused analytics approach  
- Professional-grade Power BI dashboard  
- Clear and actionable insights  

---

## 👩‍💻 Author
**Priyanka K**  
MSc Data Science  

---


