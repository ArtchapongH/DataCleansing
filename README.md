# Data Cleansing with Python

This folder included projects those demostrate how I use Python to explore, manipulate, and clean data set.

- ### Project 1 : Clean Customer Call List Data
    - Remove duplicate rows
    - Drop unused columns
    - Strip unwanted characters from 'Last_Name' column
    - Get rid non numuric characters from 'Phone_Number' column and format it to be readable
    - Split 'Address' column to 'Street Address', 'State', and 'Zip Code' column
    - Replace value to standardize the answers format for whole dataset
    - Replace N/A with blank for whole dataset
    - Filter only contactable list ('Phone_Number' is not blank)
    - Reset dataset's index



- ### Project 2 : Clean Sales Order Data
    - Read CSV file with assigning column's names
    - Recheck data type of each columns
    - Check is there any duplicate rows and drop if any
    - Split 'OrderDate' column to get only year and month values and assign them to 'Year' and 'Month' columns
    - Split 'CustomerName' column to 'FirstName' and 'LastName' columns
    - Drop unused columns and reorder columns
    - Export transformed dataset as csv format to target directory
