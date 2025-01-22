# Sales-Data-Analysis

### Dashboard Link: https://app.powerbi.com/groups/me/reports/c032bcac-af24-400d-b3ca-c077bdefff84/458902675c67238ad8a4?experience=power-bi

### Problem Statement:
This data analysis was done for the company ElectroHub which deals in electronics,footwear,clothing,home appliances,accessories,kitchenware etc.
They provided me with the store dataset in excel format and wanted me to answer the following questions for them -


1.Top/Bottom 5 product by Sales/Profit/Quantity Sold.

2) How do sales trends vary over time (daily, monthly, quarterly, annually) ?

3) Show relationship between sales & profit.


4) Compare sales/profit/quantity sold between any two periods selected by the user.

5) Average discount offered in each discount category.

6) Total number of orders.

7) Show Sales/Profit/Discount/Net Sales/All remaining fields for each order that could be filtered using visual filters. (Product/Date/Customer ID/Promotion Categories)

8) Show sales by different cities.

### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is an excel file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : As since by default, profile will be opened only for 1000 rows so I need to select "column profiling based on entire dataset".
- Step 4 : I changed the datatype of many columns to further ease my calculations and added new columns using measures and calculations from the existing dataset using Power Query Editor.
- Step 5 : For null values, I ignored them as they were very few in quantity(less than 1% of the dataset). 
- Step 6 : In the report view, various visualizations were used in different pages to answer each question asked by the company
