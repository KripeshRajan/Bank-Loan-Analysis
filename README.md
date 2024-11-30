# Citi Bank Loan Analysis
![pngwing com (1)](https://github.com/user-attachments/assets/a4e18a6d-737c-4d79-96b2-68ef0c1f9757)

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

- **`Citi Bank Loan Analysis.pbix`**: The Power BI file containing the dashboard design and data model.
- **`finanacial_loan.csv`**: The raw dataset used to create the dashboard.
- **`SQL Queries Used.docx`**: SQL Queries used for the project
- **`Dataset Description.docx`**: Terminologies used in the data set
- **`Problem Statements.docx`**: Problem statements to find out from the data set
- **`README.md`**: This documentation file.
- **` image1.jpg, image2.jpg, image3.jpg`**: A preview of the Bank Loan Anlysis Dashboard for quick reference.


## Snapshot of Dashboard (Power BI Service)
![citi image1](https://github.com/user-attachments/assets/5abeb91d-999b-4e90-a5c3-d7b2f6e2e9b3)
![citi image2](https://github.com/user-attachments/assets/3e0ce4c1-ca3c-4955-8ed6-56f86c304fdc)
![citi image3](https://github.com/user-attachments/assets/3cf4a7db-357b-41dc-b707-e4fbeb7a5088)


 


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
