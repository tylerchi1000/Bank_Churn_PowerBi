# Power BI Project: Examining Customer Churn for a Banking Dataset
## Overview

This Power BI project examines customer churn for a banking dataset based on various factors such as credit score, age, gender, country, and customer balance. The purpose of this project is to gain insights into the factors that contribute to customer churn and to develop a dashboard that can help stakeholders in the banking industry to better understand and manage customer retention.

## Data Sources

The data used in this project was obtained from a banking dataset that contains information on customer demographics, credit score, account balance, and other relevant metrics. I cleaned and prepared the dataset using Power Query in Power BI.
## Data Model

In this project, I generated a data model by binning attributes such as credit score and category. This was done to group similar values together and to simplify the analysis of the data. The data model was created using Power BI's data modeling features.
![image](https://user-images.githubusercontent.com/64235016/233759728-92888bdd-7fa6-4f29-8607-54249be115b1.png)

## Dashboard

The dashboard developed for this project includes several visualizations that help to illustrate the factors that contribute to customer churn. 

![image](https://user-images.githubusercontent.com/64235016/233759714-549ed58d-7d64-4189-92d9-636f73eee2ff.png)

The repository has the following structure:

root /

├── README.md

├── source/

│   └── banking_dataset.csv

└── customer_churn.pbix

    The README.md file contains information about the project.
    The source folder contains the original CSV file used for this project.
    The customer_churn.pbix file is the Power BI file containing the dashboard and data model for this project.

# Conclusion

Customers with high balances and those with low credit score are more likely to churn.

Underperformance in age groups 41-50, 51-60, 61-70. Ideas for why this could be occuring include that they have more options, or there are policies that are not addressing this age groups needs (retirement planning?). Many customers also have a 0 balance, with a low churn rate. It should be investigated if these accounts are new, or if they are inactive (and should be relabeled). 
