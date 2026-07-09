# Customer Behavior Analysis Dashboard

A complete **customer behavior analysis project** built using **Python (Google Colab)**, **MySQL**, and **Power BI** to analyze shopping patterns, customer preferences, subscription behavior, revenue trends, and category-level sales insights.

This project transforms raw customer shopping data into meaningful business insights through **data cleaning, SQL analysis, and interactive dashboarding**.

---

## 📌 Project Overview

Understanding customer behavior is essential for improving product strategy, customer retention, and revenue growth.  
This project analyzes a retail customer shopping dataset to answer questions such as:

- Which product categories generate the highest revenue?
- How do customer age groups contribute to sales?
- What is the average purchase amount and review rating?
- How does subscription status affect customer behavior?
- Which customer segments purchase more frequently?

The project follows an end-to-end analytics workflow:
- **Python (Google Colab)** → data cleaning, preprocessing, and analysis  
- **MySQL** → structured querying and business insight extraction  
- **Power BI** → interactive dashboard creation and KPI visualization  

---

## 🎯 Objectives

The main objectives of this project are:

- Clean and preprocess raw customer shopping data
- Store and analyze the dataset using **MySQL**
- Perform customer behavior analysis using **Python**
- Identify spending patterns, category trends, and age-group-based insights
- Measure KPIs such as:
  - total customers
  - average purchase amount
  - average review rating
  - revenue by category
  - sales by category
  - subscription distribution
- Build an interactive **Power BI dashboard** for decision-making

---

## 🛠️ Tech Stack

### Languages / Tools
- **Python**
- **MySQL**
- **Power BI**
- **Google Colab**

### Python Libraries
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `mysql-connector-python`

---

## 📂 Dataset Description

The dataset contains **3,900 customer records** and includes customer demographics, product details, purchase behavior, and subscription information.

### Key Columns Used
- `customer_id`
- `age`
- `gender`
- `item_purchased`
- `category`
- `purchase_amount`
- `location`
- `size`
- `color`
- `season`
- `review_rating`
- `subscription_status`
- `shipping_type`
- `discount_applied`
- `previous_purchases`
- `payment_method`
- `frequency_of_purchases`
- `age_group`
- `purchase_frequency_days`

---

## 🔄 Project Workflow

## 1. Data Collection
The project uses a retail customer shopping behavior dataset containing information related to:
- customer demographics
- purchase history
- category preferences
- subscription details
- ratings and reviews
- payment and shipping behavior

---

## 2. Data Cleaning and Preprocessing using Python
Python was used in **Google Colab** to clean and prepare the dataset for analysis.

### Tasks performed:
- loaded dataset into pandas dataframe
- checked data types and null values
- standardized categorical values where required
- created useful analytical fields such as:
  - `age_group`
  - `purchase_frequency_days`
- validated numeric fields like `purchase_amount` and `review_rating`
- prepared cleaned data for SQL and Power BI analysis

### Python Analysis Performed
- customer distribution analysis
- category-wise purchase behavior
- average purchase amount analysis
- review rating analysis
- age-group revenue analysis
- subscription behavior exploration

---

## 3. SQL Analysis using MySQL
The cleaned dataset was imported into **MySQL** for structured querying and business insight generation.

### SQL Tasks Performed
- created database and tables
- imported cleaned customer shopping data
- wrote analytical SQL queries for KPI extraction
- used aggregation, filtering, grouping, and ordering for insight generation

### Sample SQL Business Questions Answered
- How many total customers are present?
- What is the average purchase amount?
- What is the average review rating?
- Which category generates the highest revenue?
- Which category has the highest sales volume?
- How is revenue distributed across age groups?
- What percentage of customers have subscriptions?
- Which gender contributes more to purchases?
- What is the distribution of product purchases across categories?

### SQL Concepts Used
- `SELECT`
- `WHERE`
- `GROUP BY`
- `ORDER BY`
- `HAVING`
- `COUNT()`
- `SUM()`
- `AVG()`
- `CASE WHEN`
- subqueries (where needed)

---

## 4. Dashboard Development in Power BI
The final cleaned data and SQL-derived insights were visualized in **Power BI** using an interactive dashboard.

---

# 📊 Dashboard Features

The dashboard provides a compact business view of customer behavior with filters and KPI cards.

## KPI Cards
- **Number of Customers:** `3.9K`
- **Average Purchase Amount:** `$59.76`
- **Average Review Rating:** `3.75`

## Interactive Filters / Slicers
- **Gender**
- **Subscription Status**
- **Category**

## Visualizations Included

### 1. Subscription Status Distribution
Shows the proportion of customers with and without subscriptions.

### 2. Revenue by Age Group
Compares purchase revenue across:
- young adults
- adults
- middle-aged customers
- senior customers

### 3. Revenue by Category
Displays total purchase amount by category:
- Clothing
- Accessories
- Footwear
- Outerwear

### 4. Sales by Category
Shows category-wise customer sales contribution and helps identify the most active product categories.

---

# 📈 Key Insights from the Dashboard

Based on the dashboard:

- **Clothing** is the highest-performing category in both **revenue** and **sales**
- **Accessories** is the second strongest category
- **Outerwear** contributes the least revenue among the shown categories
- **Young adults** and **middle-aged customers** contribute strongly to total revenue
- A large majority of customers are **non-subscribers**
- The average purchase amount is around **$59.76**
- The average customer review rating is **3.75**

---

## 🖼️ Dashboard Preview

> Add your dashboard screenshot inside the repository and update the image path below.

```md
![Customer Behavior Dashboard](images/customer_behavior_dashboard.png)
```

If your screenshot is already inside an `images/` folder, this section will display the Power BI dashboard directly in GitHub.

---

## 📁 Project Structure

```bash
Customer-Behavior-Analysis/
│
├── data/
│   ├── customer_shopping_behavior.csv
│   └── cleaned_customer_data.csv
│
├── notebooks/
│   └── customer_behavior_analysis.ipynb
│
├── sql/
│   └── customer_behavior_analysis.sql
│
├── powerbi/
│   └── customer_behavior_dashboard.pbix
│
├── images/
│   └── customer_behavior_dashboard.png
│
└── README.md
```

---

# 🚀 How to Run the Project

## 1) Python / Google Colab
- Upload the dataset to Google Colab
- Open the notebook
- Install required libraries if needed
- Run preprocessing and EDA cells

## 2) MySQL
- Create a database in MySQL
- import the cleaned dataset into a table
- execute SQL queries from the SQL file to generate insights

## 3) Power BI
- Open the `.pbix` dashboard file
- connect it to the cleaned dataset or SQL output
- refresh visuals if required

---

# 📌 Example Business Use Cases

This project can help businesses:
- identify high-revenue product categories
- understand customer purchase behavior
- analyze age-group and gender-based shopping trends
- evaluate the impact of subscriptions on customer engagement
- improve inventory planning based on category performance
- support targeted marketing campaigns

---

# 🔮 Future Enhancements

This project can be extended further by adding:

- **RFM analysis** (Recency, Frequency, Monetary)
- **Customer segmentation** using clustering
- **Churn prediction model**
- **Recommendation system**
- **Time-series sales forecasting**
- **Power BI drill-through pages**
- **Automated MySQL → Power BI refresh pipeline**

---

# 🧠 Skills Demonstrated

This project demonstrates practical skills in:

- data cleaning and preprocessing
- exploratory data analysis
- SQL querying and aggregation
- KPI reporting
- dashboard design
- customer behavior analytics
- business intelligence reporting

---

# 👨‍💻 Author

**Sriharsha Devulapally**  
B.Tech in Artificial Intelligence and Data Science  
Interested in **Data Analytics, Machine Learning, SQL, and Business Intelligence**

---

# ⭐ If you like this project
If you found this project useful, consider giving this repository a **star** on GitHub.
