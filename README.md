# Bank Loan Analysis
![419-4194456_american-national-bank-design-for-america-hd-png-removebg-preview](https://github.com/user-attachments/assets/bb83e50a-8a7e-4417-b62d-5e3c9acaf1ce)
### Dashboard Link : https://app.powerbi.com/view?r=eyJrIjoiNzlmNjUwOTktMzYxMS00ODM2LWI1NDctN2VjMjRhMjk3MTdkIiwidCI6ImVkNTcxY2M5LWYxNGUtNGFiOS1hZjY4LTkzOTIyNjY0ZWQzZiJ9

## Overview

This Power BI dashboard provides a comprehensive view of bank loan performance, customer demographics, and key trends. It aims to help analysts and decision-makers gain insights into loan approval rates, loan performance, and customer behavior.

## Key Metrics and Visualizations

### 1. Overall Loan Performance:

- Total loan applications, funded amount, and amount received
- Average interest rate and debt-to-income ratio
- Loan status distribution (fully paid, charged off, current)
- Good vs. bad loan comparison

### 2.Loan Applications and Trends:
- Monthly loan application trends
- State-wise distribution of applications
- Loan term distribution
- Borrower employee tenure analysis
- Loan purpose analysis
- Home ownership analysis
### 3. Customer Demographics:

- Detailed information about individual loans, including:
  - Purpose
  - Home ownership
  - Grade
  - Subgrade
  - Issue date
  - Funded amount
  - Interest rate
  - Installment
  - Total amount received

## Steps followed 

- `Step 1` : Importing Data from CSV file to MS SQL Server.
- `Step 2` : Creating a new Data base in MS SQL Server and Firing queries to solve the business problems
- `Step 3` : Importing data from MS SQL Server to Power BI desktop.
- `Step 4` : Creating an interactive dashboard in PowerBI.
- `Step 5` : Validating Results generated in PowerBI with SQL Server.
- `Step 6` : Publishing the dashboard to PowerBI Service.

## File Structure

- **`Bank Loan Analysis.pbix`**: The Power BI file containing the dashboard design and data model.
- **`finanacial_loan.csv`**: The raw dataset used to create the dashboard.
- **`SQL Queries Used.docx`**: SQL Queries used for the project
- **`Dataset Description.docx`**: Terminologies used in the data set
- **`Problem Statements.docx`**: Problem statements to find out from the data set
- **`README.md`**: This documentation file.
- **` Preview1.jpg, Preview2.jpg, Preview3.jpg`**: A preview of the Bank Loan Anlysis Dashboard for quick reference.


## Snapshot of Dashboard (Power BI Service)
![BL3](https://github.com/user-attachments/assets/0d8b92e7-8d81-4298-bddb-2a35d7638572)
![BL2](https://github.com/user-attachments/assets/0480fa52-00dc-4a7a-8c36-bbc5cc164893)
![BL1](https://github.com/user-attachments/assets/0cee1cbd-d96b-4278-8824-39e9da7c582c)

 


# Key Insights


- The bank seems to have a good track record with a high percentage of fully paid loans.
-  Majority of the loans issued is Good Loan `(86.18%)`
- Debt consolidation is the primary reason for loans `(47%)`
- Borrowers with longer employee tenure appear to be more likely to take out loans `(23%)`
- A significant portion of borrowers home ownership type is rent (47.8%) or have a mortgage `(44.58%)`
- Most loans have a term of 36 months `(73.2%)`
- Average Interest rate of the bank is  `12.05%`
- Average Debt-to-Income (DTI) ratio is `13.33%` 
- California state have the maximum number of loan applications `(18%)`




## Software Used

- **Power BI Desktop** - Version: 2.136.1202.0 
- **SQL Server Management Studio**- 20.0
- **Microsoft Office**-Version 2021
