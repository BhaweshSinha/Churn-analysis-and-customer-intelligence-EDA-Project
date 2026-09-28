# Churn Analysis and Customer Intelligence

A data analysis project focused on understanding customer churn, subscription behavior, customer satisfaction, and retention opportunities using Python, Pandas, NumPy, Matplotlib, Seaborn, and SQLite.

## 📌 Project Overview

This project analyzes customer, subscription, and support data to identify patterns associated with customer churn and customer behavior.

The workflow includes:

* SQLite database integration
* Data import and transformation
* Data cleaning and preprocessing
* Exploratory Data Analysis (EDA)
* Customer analysis
* Subscription analysis
* Support and satisfaction analysis
* Churn investigation
* Data visualization
* Business-oriented insights

## 🗃️ Dataset Structure

The project works with three main data tables:

### Customer Data

Contains customer-level information such as:

* Customer ID
* Customer name
* Country
* State
* Gender
* Date of birth
* Interests
* Pincode

### Subscription Data

Contains subscription and churn-related information:

* Subscription start date
* Subscription type
* Renewal date
* Plan type
* Contract type
* Cancellation date
* Cancellation reason
* Monthly charges
* Customer Lifetime Value (CLTV)
* Churn score

### Support Data

Contains customer support information:

* Customer ID
* Complaint date
* Escalations
* CSAT score
* Customer comments

## 🔄 Project Workflow

```text
Raw Excel Data
      ↓
SQLite Database
      ↓
Data Import
      ↓
Data Cleaning & Preprocessing
      ↓
Exploratory Data Analysis
      ↓
Customer Analysis
      ↓
Subscription Analysis
      ↓
Support & Satisfaction Analysis
      ↓
Churn Analysis
      ↓
Visualizations & Business Insights
```

## 🧹 Data Cleaning

The preprocessing stage includes:

* Renaming columns for clarity
* Removing unnecessary columns
* Converting date fields to appropriate datetime types
* Standardizing categorical values such as gender
* Handling missing country values using state-country relationships
* Checking data types and missing values

## 📊 Analysis Areas

The analysis investigates relationships between churn and factors such as:

* Subscription type
* Plan type
* Contract type
* Monthly charges
* Customer lifetime value
* Churn score
* Cancellation reasons
* Customer support interactions
* Escalations
* CSAT scores
* Customer demographics

## 🛠️ Technologies Used

* **Python**
* **Pandas** — data manipulation and analysis
* **NumPy** — numerical operations
* **Matplotlib** — data visualization
* **Seaborn** — statistical visualization
* **SQLite** — relational data storage and querying
* **Jupyter Notebook** — analysis workflow

## 📁 Project Files

```text
Churn Analysis and Customer Intelligence/
│
├── churn_analysis.ipynb
├── customer_churn_data_raw.xlsx
├── customer_churn.db
└── README.md
```

## 🎯 Objective

The primary objective is to transform raw customer data into meaningful insights that can help understand churn behavior, identify potential risk factors, evaluate customer satisfaction, and support data-driven customer retention strategies.

## 👤 Author

**Bhawesh Sinha**
B.Tech in Data Science
