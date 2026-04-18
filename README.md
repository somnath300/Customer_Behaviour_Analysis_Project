

## Overview

This project demonstrates an end-to-end data analytics workflow, covering data loading, cleaning, exploration, querying, visualization, and reporting. The goal is to extract actionable insights from raw data and present them through an interactive dashboard and presentation.

---

## Dataset

* Format: CSV 
* Description:
* The dataset contains customer-level transactional data, including:
*  o	Customer demographics (Age, Gender)
*  o	Product details (Item Purchased, Category, Size, Color)
*  o	Purchase behaviour (Purchase Amount, Discounts, Shipping Type)
*  o	Engagement metrics (Review Ratings, Subscription Status)
*  o	Purchase history (Previous Purchases)


                 

---

## Tools & Technologies

* **Python** (Pandas)
* **SQL** (PostgreSQL)
* **Power BI** (Dashboard & visualization)
* **Gamma** (Presentation creation)
* **Jupyter Notebook**

---

## Project Steps

### 1. Data Loading and Validation(using EXCEL)

* Loaded CSV data into Excel
* Checked For:
*    •	Missing Values
*    •	Check data quality before analysis

     
<img width="931" height="486" alt="image" src="https://github.com/user-attachments/assets/d054f302-fa3c-47ea-a473-bd613657ec7b" />


### 3. Exploratory Data Analysis (Python - Pandas)

* Loaded dataset into Jupyter Notebook

* Used Pandas for:
* •	Data inspection (head(), info(), describe())
* •	Preparing clean, analysis-ready data
* •	Feature engineering (e.g., age group segmentation)
* •	Exported processed data for SQL analysis

 <img width="935" height="473" alt="image" src="https://github.com/user-attachments/assets/cae904ef-ab37-46c6-b689-b17945c635c2" />


### 4. Business Questions & SQL Analysis (PostgreSQL)

* Loaded cleaned data into database
* Wrote queries to extract insights
  
<img width="1034" height="753" alt="image" src="https://github.com/user-attachments/assets/cd42bc08-9491-40b3-a001-f13aefdc9714" />



### 5. Dashboard Creation

* Built an interactive Power BI dashboard
* Included visual insights
* Trend analysis visuals
* Focused on clarity and usability
  
  <img width="1073" height="623" alt="image" src="https://github.com/user-attachments/assets/211f8e90-26ce-461a-967e-24dbe9475dc1" />


### 6. Reporting & Presentation

* Summarized key findings in a report
* Created a presentation using Gamma

## Results & Insights

* Identified key trends and patterns in the dataset
* Highlighted performance metrics and anomalies
* Provided actionable recommendations based on data -
*  • Boost Subscriptions – Promote exclusive benefits for subscribers.
*  • Customer Loyalty Programs – Reward repeat buyers to move them into the 'Loyal' segment.
*  • Review Discount Policy – Balance sales boosts with margin control.
*  • Product Positioning – Highlight top-rated and best-selling products in campaigns.
*  • Targeted Marketing – Focus efforts on high-revenue age groups and express-shipping use
  


## Future Improvements

* Automate data pipeline
* Deploy dashboard online
* Add advanced analytics (ML models)

