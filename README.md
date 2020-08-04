# PowerBI Projects

This project is meant to show my skills in Power BI.

## Installation / Software Needed
Power BI 2.83.*

## Project Data Description

The dataset used is [Microsoft Contoso BI Demo Dataset for Retail Industry](https://www.microsoft.com/en-us/download/details.aspx?id=18279)

A fictitious retail demo dataset used for presenting Microsoft Business Intelligence products.
Details
Version 2.1

## File Descriptions
1. [Project - Getting Data and Loading - Part 1](https://github.com/ahmet-cigil/PowerBI_Projects/blob/master/1.%20Contoso%20Project%20-%20getting%20and%20loading%20Data%20-%20Part%201.pbix)
  - Understand business and analysis of project requirements
  - Connect to data
  - Load data

2. Common Data Transformations with Power Query:  

  [Part 2](https://github.com/ahmet-cigil/PowerBI_Projects/blob/master/1.%20Contoso%20Project%20-%20remove%20columns%2C%20rename%20columns%20and%20tables%2C%20detect%20data%20types%20-%20Part%202.pbix)
  
- Remove columns with missing and unimportant columns
- Renamed column names to user-friendly ones
- Renamed table names to user-friendly ones
- Transform by detecting data types

 [Part 3](https://github.com/ahmet-cigil/PowerBI_Projects/blob/master/1.%20Contoso%20Project%20-%20filter%2C%20add%20and%20remove%20columns%2C%20merge%20tables%20-%20Part%203.pbix)
  
- Filter data: Filtered data (date =< 2007)
- Add new columns and removed old ones: Merge 2 columns into 1 column 
  ("Manager First Name" and "Manager Last Name" merged into "Manager Full Name)
- Repetitive words removed ("Contoso" word removed from "Store Name" column)
- Merging tables ("Product" table is merged by "Product Subcategory Key", "Product" table is merged by "Product Category", removed old columns used to execute merging)
- Disable loading "Product Category" and "Product Subcategory" as they are merged already to the final "Product Master" created as a star schema instead of snowflake schema.
