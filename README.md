# Online Retail Sales Insights

Project overview
This project is looking at sales of an UK based and registered non-store online retailer and determining whether time affects purchasing behaviour across 42 countries. The company sells unique all occasion gifts mainly to wholesale customers.

Hypothesis
People are more likely to shop online during a certain time of the day or week of the day.

People are more likely to shop in certain months of the year (i.e. Christmas season or end of financial year ).

People are more likely to buy in higher quantities at lower prices. 

Data Source
URL: https://archive.ics.uci.edu/ml/datasets/online+retail
Date retrieved: Tuesday 14th September 2021
Data format: XLSX (converted to CSV)
Author: Dr Daqing Chen, Director: Public Analytics group.
Organisation:  School of Engineering, London South Bank University, London SE1 0AA, UK.
How was the data retrieved?: Downloaded the CSV file
Data period: From 2009 to 2011
Data points: Over 1 million

Data wrangling process
Separated two tabs from Excel and saving it as two separate CSV files
Merged two CSV files
 Removing any data points that have:
Quantity less than zero
Price less than zero
Removing unspecified countries
Rename column data
Renamed column names
Changed data type to appropriate type
Split ‘Date and time’ into separate columns
