# 📊 Promotional Campaign Analysis

## 📌 Project Overview

This project was completed as part of the **Codebasics Virtual Internship**.

The objective of this project is to evaluate the effectiveness of promotional campaigns by analyzing customer purchasing behavior, sales performance, and revenue growth using Exploratory Data Analysis (EDA).

The analysis follows a business-oriented approach by answering real-world business questions and providing actionable recommendations based on data.

---

## 🏢 Business Problem

Promotional campaigns are designed to increase customer engagement, sales volume, and revenue. However, not every promotion performs equally across products, cities, and campaigns.

This project aims to answer questions such as:

- Which cities responded best to promotions?
- Which product categories generated the highest sales?
- Which promotion type delivered the highest revenue?
- How did promotions impact revenue across different categories?
- Which regions require improved promotional strategies?

---

## ⭐ Data Model

The dataset follows a **Star Schema** consisting of:

### Fact Table
- **fact_events**
  - Product Code
  - Campaign ID
  - Store ID
  - Base Price (Before & After Promotion)
  - Quantity Sold (Before & After Promotion)
  - Promotion Type

### Dimension Tables

- **dim_products**
- **dim_campaigns**
- **dim_stores**

The fact table was joined with dimension tables using **Pandas merge()** operations to perform multidimensional analysis.

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Removed duplicate records
- Handled missing values using **Median Imputation**
- Created derived KPIs
- Joined fact and dimension tables
- Prepared the dataset for exploratory analysis

---

## 📈 Key Performance Indicators (KPIs)

### Incremental Revenue Percentage (IR%)

Measures the percentage increase in revenue after promotion.

\[
IR\%={Revenue_{After}-Revenue_{Before}}{Revenue_{Before}}\times100
\]

---

### Incremental Sold Units Percentage (ISU%)

Measures the percentage increase in quantity sold after promotion.

\[
ISU\%={Quantity_{After}-Quantity_{Before}}{Quantity_{Before}}\times100
\]

---

## 📊 Exploratory Data Analysis

The following business analyses were performed:

- Store Distribution Across Cities
- Category-wise Sales Contribution
- Distribution of Quantity Sold Before Promotion
- Correlation between Price and Sales
- Promotion Effectiveness Across Cities
- Promotion Type Performance
- Revenue Before vs After Promotions

---

## 🔍 Key Insights

### 🏪 Store Distribution

- Bengaluru has the highest retail presence.
- Chennai and Hyderabad are the next largest markets.
- Smaller cities provide opportunities for expansion.

---

### 🛒 Product Performance

- Grocery & Staples contributes the highest sales volume.
- Combo1 recorded the highest revenue growth.
- Personal Care showed comparatively weaker performance.

---

### 📍 City Performance

- Chennai achieved the highest Incremental Sold Units Percentage (ISU%).
- Visakhapatnam recorded the lowest promotional uplift.

---

### 💰 Revenue Analysis

- Promotions significantly increased revenue across most categories.
- Combo1 delivered the highest revenue improvement.
- Personal Care requires a revised promotional strategy.

---

### 📉 Correlation Analysis

- A weak positive correlation (0.27) exists between post-promotion price and sales quantity.
- Promotion type and customer demand have a greater influence on sales than price alone.

---

## 💡 Business Recommendations

- Prioritize inventory for Grocery & Staples during promotional campaigns.
- Use BOGOF promotions to maximize sales volume.
- Use Cashback promotions to maximize revenue.
- Implement city-specific promotional strategies.
- Redesign promotional campaigns for Personal Care products.

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Repository Structure

```
Promotional-Campaign-Analysis/
│
├── datasets/
├── images/
├── Promotional_Campaign_Analysis.ipynb
├── Promotional_Campaign_Analysis.pptx
├── README.md
```

---

## 🎥 Project Presentation

A detailed presentation video explaining:

- Dataset Overview
- Star Schema
- Data Cleaning
- Exploratory Data Analysis
- Business Insights
- Recommendations

is available in the LinkedIn post created for this project.

---

## 🙏 Acknowledgements

This project was completed as part of the **Codebasics Virtual Internship** to strengthen practical skills in Data Analytics, Business Intelligence, Data Visualization, and Data Storytelling.

Special thanks to **Dhaval Patel**, **Hemanand Vadivel**, and the **Codebasics** team for providing this industry-oriented learning opportunity.

---

## 📬 Connect With Me

**Amey Barbadikar**

LinkedIn: *(https://www.linkedin.com/in/amey-barbadikar-1b7045106/)*


---
