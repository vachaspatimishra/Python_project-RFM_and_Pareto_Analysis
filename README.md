# Python Project – Customer Segmentation using RFM & Pareto Analysis

## Overview

This project performs **Customer Segmentation using RFM Analysis** and **Pareto Analysis** on customer transaction data and customer demographics data using Python.

The project focuses on:

* Cleaning and preparing customer transaction data
* Calculating RFM metrics (Recency, Frequency, Monetary)
* Segmenting customers based on spending behavior
* Identifying high-value customers
* Performing Pareto Analysis to understand revenue contribution
* Visualizing customer insights using charts

---

## Objectives

* Analyze customer purchasing behavior
* Identify loyal and high-value customers
* Segment customers for targeted marketing strategies
* Understand revenue distribution among customers
* Apply the Pareto Principle (80/20 Rule) in business analytics

---

## Dataset Information

The project uses two datasets:

### 1. Customer Master Data

Contains customer-related information such as:

* CustomerID
* Customer Name
* Join Date
* Customer details

### 2. Customer Transactions Data

Contains transaction history such as:

* CustomerID
* Transaction Date
* Purchase Amount
* Transaction details

---

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Project Workflow

### 1. Data Loading

* Imported customer and transaction datasets
* Checked dataset structure and previewed records

### 2. Data Cleaning

* Handled incorrect data types
* Converted date columns into datetime format
* Checked missing values and duplicates
* Verified data consistency

### 3. Data Merging

* Joined customer and transaction datasets using `CustomerID`

### 4. RFM Analysis

Calculated:

* **Recency** → How recently a customer purchased
* **Frequency** → How often a customer purchased
* **Monetary** → Total amount spent by a customer

### 5. RFM Scoring

* Assigned scores using quantiles
* Created combined RFM segments
* Labeled customer groups such as:

  * Champions
  * Big Spenders
  * Frequent
  * Recent
  * Lost Customers

### 6. Data Visualization

Created visualizations for:

* Customer segments
* Revenue contribution
* Spending patterns
* Pareto Analysis

### 7. Pareto Analysis

* Analyzed contribution of top customers to total revenue
* Evaluated whether the dataset follows the 80/20 Pareto Principle

---

## Key Insights

* High-value customers contribute a significant share of total revenue.
* Revenue distribution is relatively balanced across the customer base.
* Customer segmentation helps identify loyal, inactive, and premium customers.
* Pareto Analysis provides insights for retention and marketing strategies.

---

## File Structure

```text
├── Python_Mini_Project_Vachaspati_Mishra.ipynb
├── Customer_Master_Data.csv
├── Customer_Transactions.csv
└── README.md
```

---

## Learning Outcomes

Through this project, I learned:

* Data cleaning and preprocessing
* Customer analytics techniques
* RFM segmentation methodology
* Pareto Analysis implementation
* Exploratory Data Analysis (EDA)
* Data visualization using Python

---

## Future Improvements

* Build an interactive dashboard using Power BI or Tableau
* Automate customer segmentation
* Add predictive analytics for customer retention
* Deploy the project as a web application

---

## Author

**Vachaspati Mishra**

If you found this project useful, feel free to star the repository.
