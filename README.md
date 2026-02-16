# Customer_Insights and Engagement_Analysis
This is a data analytics project showcasing the customer behavior and engagement analysis using python, postgresql and powerbi.
Here’s a clean, professional **README.md** you can directly use for your GitHub repository. I’ve written it in a recruiter-friendly and industry-standard format 👇

---

# 📊 Customer Insights & Engagement Analysis

## 📌 Project Overview

This project analyzes **customer purchasing behavior** using **3,900 transactions** across multiple product categories.
The goal is to uncover **spending trends, customer segments, product preferences, and subscription behavior** to support data-driven business decisions.

The analysis combines **Python (EDA & data cleaning)**, **SQL (business insights)**, and **Power BI (visualization)**.

---

## 📁 Dataset Summary

* **Total Rows:** 3,900
* **Total Columns:** 18

### Key Features

* **Customer Demographics:**

  * Age, Gender, Location, Subscription Status

* **Purchase Details:**

  * Item Purchased, Category, Purchase Amount
  * Season, Size, Color

* **Shopping Behavior:**

  * Discount Applied
  * Promo Code Used
  * Previous Purchases
  * Purchase Frequency
  * Review Rating
  * Shipping Type

* **Missing Data:**

  * 37 missing values in the `review_rating` column

---

## 🐍 Exploratory Data Analysis (Python)

EDA and data preprocessing were performed using **Python** and **pandas**.

### Steps Performed

* **Data Loading:**
  Imported the dataset using pandas.

* **Initial Exploration:**

  * Used `df.info()` to inspect data types and structure
  * Used `df.describe()` for summary statistics

* **Missing Value Treatment:**

  * Imputed missing values in `review_rating` using the **median rating per product category**

* **Column Standardization:**

  * Converted column names to **snake_case** for readability and consistency

* **Feature Engineering:**

  * Created `age_group` by binning customer ages
  * Created `purchase_frequency_days` based on purchase behavior

* **Data Consistency Check:**

  * Identified redundancy between `discount_applied` and `promo_code_used`
  * Dropped `promo_code_used`

* **Database Integration:**

  * Connected Python to **PostgreSQL**
  * Loaded cleaned data into the database for SQL analysis

---

## 🛢️ Data Analysis Using SQL (PostgreSQL)

Business-focused analysis was performed using SQL queries.

### Key Business Questions Answered

1. Revenue comparison by **gender**
2. High-spending customers who **used discounts**
3. **Top 5 products** by average review rating
4. Purchase amount comparison by **shipping type**
5. Spending patterns of **subscribers vs. non-subscribers**
6. Products most **dependent on discounts**
7. **Customer segmentation** into New, Returning, and Loyal
8. **Top 3 products per category**
9. Relationship between **repeat purchases and subscriptions**
10. Revenue contribution by **age group**

---

## 📊 Power BI Dashboard

An interactive **Power BI dashboard** was created to visualize insights such as:

* Revenue trends
* Customer segments
* Subscription impact
* Product performance
* Shipping behavior

The dashboard enables quick, data-driven decision-making for stakeholders.

---

## 💡 Business Recommendations

Based on the analysis, the following actions are recommended:

* **Boost Subscriptions**
  Offer exclusive benefits and incentives for subscribers.

* **Customer Loyalty Programs**
  Reward repeat buyers to move them into the *Loyal* segment.

* **Review Discount Strategy**
  Optimize discounts to balance revenue growth and margins.

* **Product Positioning**
  Promote top-rated and best-selling products in campaigns.

* **Targeted Marketing**
  Focus marketing efforts on high-revenue age groups and express-shipping users.

---

## 🛠️ Tools & Technologies Used

* **Python:** pandas, NumPy
* **SQL:** PostgreSQL
* **Visualization:** Power BI
* **Database Integration:** Python → PostgreSQL
* **Presentation: **Gaama AI

---

## 🚀 Key Takeaways

This project demonstrates **end-to-end data analytics skills**, including:

* Data cleaning & feature engineering
* SQL-based business analysis
* Dashboard storytelling
* Actionable business recommendations


Just tell me 👍
