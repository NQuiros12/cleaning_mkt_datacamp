# Project: Cleaning Bank Marketing Campaign Data for PostgreSQL Database

### Introduction:

Personal loans are a major source of revenue for banks, with sizable interest rates generating significant profits. To optimize their marketing efforts and data analysis, banks need clean and structured data. This project involves cleaning and formatting data from a recent bank marketing campaign for a PostgreSQL database.

### Objectives:

* Data Cleaning: Clean the provided "bank_marketing.csv" file by addressing inconsistencies, missing values, and formatting errors.
* Data Reformatting: Ensure the data conforms to the specific structure and data types specified by the bank. This includes standardizing date formats, categorizing variables, and handling potential outliers.
* Data Splitting: Split the cleaned and reformatted data into three separate CSV files:
    *  "customers.csv": Containing customer information like demographics, income, and loan applications.
    *    "loans.csv": Containing loan details, including type, amount, and approval status.
    *    "marketing_contacts.csv": Containing marketing contact information and campaign interactions per customer.

### Workflow:

* Data Loading and Exploration: Load the "bank_marketing.csv" file and explore its structure, identifying data quality issues and potential inconsistencies.
* Data Cleaning: Address missing values, handle outliers, and correct formatting errors. This may involve imputing missing values, removing duplicate entries, and standardizing date formats.
* Data Reformatting: Categorize variables, convert data types to match the bank's specifications, and ensure proper data encoding.
* Data Splitting: Split the cleaned and reformatted data into three separate CSV files: "customers.csv", "loans.csv", and "marketing_contacts.csv". Each file will have specific columns and data types defined by the bank.
* Data Validation: Validate the cleaned and split data for accuracy and adherence to the bank's specifications.
