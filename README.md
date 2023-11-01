# sales_data_sample_study
### this is a sample repository to practice using GitHub
### we will conduct some analysis of a sample sales data file as an example
#
#
# Initial Analysis of sample-sales-data.csv file
## PreProcessing Requirements
### File has several columns of sales data including order quantities, dates, product lines, and customer details
### Data file appears to be reasonably clean, already arranged in columns without any missing values
## Visualization Ideas
### Time series plot of sales by quarters to study seasonality of sales
### Relative sales of product lines over time to see which products are growing/shrinking in sales
### Geographic sales over time to see which regions are growing/shrinking in sales
## Data Dictionary
### The following fields are present in the dataset:
#### ORDERNUMBER, Integer, order tracking number 
#### QUANTITYORDERED, Integer, order quantity
#### PRICEEACH, Floating Point, price per unit
#### ORDERLINENUMBER, Integer, (unsure of precise definition)
#### SALES, Floating Point, total revenue in order
#### ORDERDATE, Integer, date code
#### STATUS, Text, order status (e.g. shipped)
#### QTR_ID, Integer, quarter code
#### MONTH_ID, Integer, month code
#### YEAR_ID, Integer, year code
#### PRODUCTLINE, Text, product line description
#### MSRP, Integer, (unsure of precise definition)
#### PRODUCTCODE, Integer, (unsure of precise definition)
#### CUSTOMERNAME, Text, customer business name
#### PHONE, Text, customer business phone
#### ADDRESSLINE1, Text, address line 1
#### ADDRESSLINE2, Text, address line 2
#### CITY, Text, city
#### STATE, Text, state (if applicable)
#### POSTALCODE, Text, postal code
#### COUNTRY, Text, country
#### TERRITORY, Text, global territory
#### CONTACTLASTNAME, Text, last name
#### CONTACTFIRSTNAME, Text, first name
#### DEALSIZE, Text, deal size category (small, medium, large)
