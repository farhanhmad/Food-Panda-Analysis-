📊 FoodPanda 🐼 Orders Analysis — Data Analytics Project

📌 Project Overview

This project analyzes Foodpanda order data to uncover customer behavior, popular items, restaurant performance, and peak ordering times. The analysis uses Python (pandas, seaborn, matplotlib) in Google Colab and follows a complete data analytics workflow:

Data cleaning & preprocessing

Exploratory data analysis (EDA)

Visualization of key trends

Customer segmentation (RFM analysis & clustering)

Market basket analysis (Apriori association rules)

Actionable business insights & recommendations


The project demonstrates end-to-end data analytics skills suitable for business decision-making.


---

📂 Project Structure

Foodpanda-Analysis/
│
├── data/
│   ├── Foodpanda Analysis Dataset.csv     # Original dataset
│   ├── foodpanda_cleaned.csv              # Cleaned dataset after preprocessing
│
├── notebooks/
│   ├── foodpanda_analysis.ipynb           # Main Jupyter/Colab notebook
├── README.md                              # Project documentation (this file)

---

🚀 Getting Started

🔧 Installation

1. Clone this repository:

git clone https://github.com/farhanahmad/Foodpanda-Analysis.git
cd Foodpanda-Analysis

---

📊 Data Description

The dataset contains information about Foodpanda orders such as:

OrderID — Unique order identifier

CustomerID — Unique customer identifier

Restaurant — Restaurant name

Item — Ordered items

Quantity — Quantity of items ordered

Price — Unit price

TotalPrice — Total order price

Order Date/Time — Timestamp of the order


---

🔍 Analysis Workflow

1. Data Cleaning & Preprocessing

Removed duplicates & handled missing values

Converted columns to proper data types

Created new features: order_hour, order_dayname, order_month

Calculated TotalPrice per order


2. Exploratory Data Analysis (EDA)

Distribution of numerical and categorical features

Correlation analysis

Top restaurants and items

Orders over time


3. Visualizations

Top 10 most ordered items

Orders by hour and by weekday


4. Customer Segmentation (RFM Analysis)

Recency: Days since last order

Frequency: Number of orders

Monetary: Total spend

Segmented customers into clusters using KMeans


5. Market Basket Analysis

Used Apriori algorithm to find item associations

Derived frequent itemsets and association rules

Example: “Customers who ordered Burger often also ordered Fries”



---

📈 Key Findings

Peak Hours: Orders peak between 7 PM – 10 PM.

Busiest Days: Weekends show significantly higher orders.

High-Value Customers: A small group contributes a large share of revenue.

Item Associations: Certain items are frequently ordered together, enabling targeted combo promotions.



---

💡 Recommendations

1. Run targeted promotions during off-peak hours to increase demand.


2. Offer combo deals based on item association rules.


3. Provide loyalty rewards for top customers.


4. Optimize restaurant preparation for peak evening hours.




---

🛠️ Tools & Libraries Used

Python (pandas, numpy)

Visualization: matplotlib, seaborn

Machine Learning: scikit-learn (KMeans clustering)

Association Rules: mlxtend (Apriori)

Notebook Environment: Google Colab / Jupyter



---

📬 Contact

👤 Farhan Ahmad
📧 [farhan.ahmad53@yahoo.com]

---

⚡ This project was created as part of a Data Analytics learning journey. Feel free to fork, use, and contribute!


---
