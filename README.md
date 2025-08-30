# Customer-Segmentation-and-Retention-Strategy
This work grouped customers into cohorts to check the change in patterns that led to reduced patronage and also to see what it can do get customers to return to business activities with the company
# Hi, I'm Henry
I am a Data Science consultant with the Amdari,
currently exploring data analytics, cohort analysis, and transformation projects

My Skills & Tools
Showcase your technical skills with badges or text:
Languages: Python, SQL, R (if applicable)
Libraries: Pandas, Matplotlib, Seaborn, NumPy
Tools: Jupyter Notebook, Excel, Power BI, Git/GitHub
Other: Data Cleaning, Cohort Analysis, Communication

Currently Learning  
- Advanced SQL  
- Data Visualization (Power BI, Seaborn)  


Contact / Networking
Let people reach you:
📫 Email: xtreem3005@yahoo.com
💼 LinkedIn: www.linkedin.com/in/henry-e-02a27077





Customer Segmentation & Retention Strategy Report

This work explores an E-commerce dataset containing over 540,000 transactions across multiple countries. The primary goal is to perform a Cohort Analysis to understand customer retention patterns — i.e., how often customers return after their first purchase.
By identifying retention trends, the analysis provides insights into customer loyalty, churn behaviour, and business growth opportunities.


## Methodology
The analysis follows these key steps:
Data Cleaning & Preparation
Converted InvoiceDate to datetime format.
Removed transactions without a valid CustomerID.
Created an OrderMonth column for monthly aggregation.
Cohort Assignment
Defined cohorts by each customer’s first purchase month (CohortMonth).
Cohort Indexing
Calculated CohortIndex, which tracks how many months have passed since the first purchase.
Cohort Retention Table
Built a pivot table showing the number of unique returning customers per cohort over time.
Visualization
Generated a heatmap to illustrate retention trends visually.
## Installation

Install my-project with npm

```bash
  npm install my-project
  cd my-project
```
    
## Deployment

To deploy this project run
# Cohort Analysis of E-commerce Transactions

## Overview
This project analyzes an e-commerce dataset to perform cohort analysis, focusing on customer retention over time.

## Dataset
- Transactions: 541,909
- Fields: InvoiceNo, InvoiceDate, CustomerID, StockCode, Description, Quantity, UnitPrice, Country

## Installation
Clone this repository and install the required libraries:

```bash
git clone https://github.com/Enadiakhere/Customer-Segmentation-Retention-Analysis.git
cd Customer-Segmentation-Retention-Analysis
pip install -r requirements.txt

```bash
  npm run deploy
```


## Structure
## Findings
Cohort analysis is a powerful way to track customer lifecycle behaviour.
Businesses should focus on early engagement strategies to improve retention beyond the first month.
Comparing early vs. later cohorts reveals whether marketing or product changes influenced loyalty.
## Tools used 
Python
Pandas – data manipulation
Matplotlib / Seaborn – visualization
Jupyter Notebook – documentation & analysis
## Authors

- Henry Emagbon (https://github.com/Enadiakhere)


## Feedback

If you have any feedback, please reach out to us at xtreem3005@yahoo.com

