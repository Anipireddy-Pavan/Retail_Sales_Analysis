# Retail_Sales_Analysis
Exploratory Data Analysis on retail sales data using Python, Pandas, Matplotlib, Seaborn, and statistical techniques to uncover sales trends and customer behaviour.

# 🛒 Retail Sales Analysis – Exploratory Data Analysis (EDA)

##  Project Overview

Retail businesses generate large volumes of transactional data, but transforming this raw data into **actionable business insights** is often challenging.

This project focuses on performing **Exploratory Data Analysis (EDA)** and **statistical analysis** on retail sales data to uncover:

* Sales trends over time
* Customer behavior patterns
* Key revenue drivers
* Business insights to support data-driven decision-making

The analysis is implemented using **Python**, leveraging popular data analysis and visualization libraries.

---

##  Objectives

* Perform Exploratory Data Analysis (EDA) on retail sales data
* Identify seasonal and regional sales trends
* Analyze customer segments and revenue contribution
* Apply statistical techniques to support business decisions
* Communicate insights using effective data visualization

---

##  Dataset Description

The dataset contains retail transaction-level data with the following columns:

| Column Name   | Description                                  |
| ------------- | -------------------------------------------- |
| Order_id      | Unique identifier for each order             |
| Order_Date    | Date when the order was placed               |
| Region        | Sales region (North, South, East, West)      |
| Customer_Type | Type of customer (Retail, Wholesale, Online) |
| Product_Price | Price of the product                         |
| Quantity      | Quantity purchased                           |
| Revenue       | Total revenue generated per order            |

---

##  Tools & Technologies

* **Python**
* **Pandas** – Data manipulation & analysis
* **NumPy** – Numerical computations
* **Matplotlib & Seaborn** – Data visualization
* **SciPy** – Statistical testing
* **Jupyter Notebook** – Interactive analysis

---

## 🔍 Project Workflow

### 1️ Data Loading & Understanding

* Loaded the dataset using Pandas
* Reviewed data structure, data types, and summary statistics
* Checked for missing and duplicate values

### 2️ Data Cleaning

* Handled missing values (if present)
* Removed duplicate records
* Converted `Order_Date` into datetime format

### 3️ Feature Engineering (Date Features)

Extracted useful time-based features:

* Year
* Month & Month Name
* Quarter
* Day of Week
* Weekend indicator

These features enabled **seasonal and trend analysis**.

---

## Exploratory Data Analysis (EDA)

###  Sales Trend Analysis

* Monthly revenue trend analysis
* Quarterly sales performance
* Weekend vs weekday revenue comparison

###  Regional Performance

* Identified top-performing and underperforming regions
* Compared revenue distribution across regions using bar charts and boxplots

### Customer Analysis

* Revenue contribution by customer type
* Comparison of average revenue across customer segments

---

## 📐 Statistical Analysis

###  Correlation Analysis

* Examined relationships between Product Price, Quantity, and Revenue
* Identified strong correlation between Quantity and Revenue

### Outlier Detection

* Used **Interquartile Range (IQR)** to understand revenue distribution and detect outliers

###  Hypothesis Testing (t-test)

**Business Question:**

> Does average revenue differ between Retail and Wholesale customers?

* Applied independent t-test
* Result showed **no statistically significant difference** in average revenue between the two customer groups

---

##  Visualizations Used

* Line charts for monthly trends
* Bar charts for regional sales
* Pie chart for customer revenue contribution
* Boxplots for revenue distribution
* Heatmap for correlation matrix

These visualizations help in **visual storytelling and stakeholder communication**.

---

##  Key Business Insights

* Sales exhibit clear **seasonal trends** across months and quarters
* Certain regions consistently outperform others in revenue generation
* Revenue contribution varies across customer segments
* Quantity sold has a stronger impact on revenue than product price
* No significant difference in average revenue between Retail and Wholesale customers

---

##  Conclusion

This project demonstrates how **EDA and basic statistical techniques** can convert raw retail data into meaningful insights that support business decisions.

The approach can be extended further using:

* Advanced statistical models
* Machine learning forecasting
* Interactive dashboards (Power BI / Tableau)

---

##  Future Enhancements

* Add customer segmentation (New vs Returning)
* Build predictive sales forecasting models
* Create an interactive dashboard
* Automate reporting pipelines

---

##  Author

**Pavan Anipireddy**
Aspiring Data Analyst
Bengaluru, Karnataka

---

If you found this project useful, feel free to star the repository!
