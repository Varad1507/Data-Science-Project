📌 Project Overview
This project focuses on analyzing and cleaning a dataset of used car listings from Quikr, an online marketplace. The dataset contains inconsistencies, missing values, and formatting issues that require preprocessing. By cleaning the dataset, we can extract meaningful insights about the used car market.

🎯 Objectives
Clean and preprocess the dataset to remove inconsistencies
Standardize column values for better readability and analysis
Handle missing and incorrect values
Extract insights from the dataset

Data Cleaning & Preprocessing
Identified Data Issues
name: Contains inconsistent values and sometimes includes company names.
company: Many names are incorrect, such as "Used" or "URJENT".
year: Contains invalid entries, non-numeric values, and incorrect data types.
price: Includes "Ask for Price" and comma-separated values, requiring conversion to numeric.
kms_driven: Has inconsistent text formats and non-numeric values.
fuel_type: Contains missing values that need to be handled.

Steps Taken to Clean the Data
 Standardized car names by removing unnecessary details
 Filtered out invalid year values and converted them to integers
 Removed non-numeric characters from price and converted it to a numerical format
 Extracted numeric values from kms_driven and converted them to integers
 Handled missing values in fuel_type

Insights & Analysis
After cleaning the dataset, we can analyze trends in the used car market, such as:
 The most popular car brands and models
 Price distribution of used cars
 The effect of kilometers driven on car price
 Common fuel types used in second-hand cars

Conclusion
This project improves data quality for Quikr's used car listings, making it easier to extract insights and perform market analysis. By cleaning and preprocessing the data, we enable better decision-making for both buyers and sellers.


