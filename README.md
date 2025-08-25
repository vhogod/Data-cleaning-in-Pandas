# Data-cleaning-with-Pandas

## Description
this project demonstrates data cleaning technique using the pandas library in python. I process customer call center data to handle common data issues such as missing value, duplicates, inconsistent formats, and outliers preparing the data for analysis

## data cleaning steps
The script performs the following cleaning tasks:

•  Handling Missing Values: Imputes missing numerical values with the median and categorical values with the mode.

•  Removing Duplicates: Drops duplicate rows based on all columns.

•  Data Type Conversion: Converts columns (dates to datetime, strings to categorical).

•  Outlier Detection: Identifies and removes outliers using the IQR method.

•  Standardizing Formats: Ensures consistent text case and removes extra whitespace.

•  Encoding Categorical Variables: Applies one-hot encoding for compatibility.

## dataset
Dataset

•  Name: [ Customer call list Data]

•  Source: [ Kaggle]

•  Format: CSV

•  Columns: [ CustomerID	First_Name	Last_Name	Phone_Number	Address	Paying Customer	Do_Not_Contact	Not_Useful_Column]
•  Size: [ 20 rows, 8 columns]
