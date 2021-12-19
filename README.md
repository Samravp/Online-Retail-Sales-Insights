# Online Retail Sales Insights

**Project overview**

This project is looking at sales of an UK based and registered non-store online retailer and determining whether time affects purchasing behaviour across 42 countries. The company sells unique all occasion gifts mainly to wholesale customers.

![image](https://user-images.githubusercontent.com/85004202/134448057-f02fc9bc-8f0e-4fee-8d95-02fd511d52a6.png)

**Team Members**

- [Zachary Breen](https://github.com/chewy-program)
- [Miley Kotamee](https://github.com/Wisdom-Miley)
- [Nicholas Chua](https://github.com/nickchuasl)


**Hypothesis**

- People are more likely to shop online during a certain time of the day or week of the day.

- People are more likely to shop in certain months of the year (i.e. Christmas season or end of financial year ).

- People are more likely to buy in higher quantities at lower prices. 

**Data Source**

- URL: https://archive.ics.uci.edu/ml/datasets/online+retail
- Date retrieved: Tuesday 14th September 2021
- Data format: XLSX (converted to CSV)
- Author: Dr Daqing Chen, Director: Public Analytics group.
- Organisation:  School of Engineering, London South Bank University, London SE1 0AA, UK.
- How was the data retrieved?: Downloaded the CSV file
- Data period: From 2009 to 2011
- Data points: Over 1 million

**Data wrangling process**

- Separated two tabs from Excel and saving it as two separate CSV files
- Merged two CSV files
- Removing any data points that have:
   - Quantity less than zero
   - Price less than zero
- Removing unspecified countries
- Rename column data
- Renamed column names
- Changed data type to appropriate type
- Splitted ‘Date and time’ into separate columns

**Analysis**
In this project we drill down to analyse below topics;

- Volume of monthly orders per year
- Annual sale increase/decrease between 3 year of the data  
- Total average volume increase/decrease between 3 year of the data  
- Number of orders per day
- Average unit price of order for each day
- Money spent vs quantity purchased for all customers and trend 
- Customers who spent and bought the most

The questions that this analysis answer include;
- Which Country had the highest order quantity?
- What time during the day has the most sale volume?

In addition, this analysis showcases a heatmap that presents sale correlation in each country. (NOTE:Gmaps API Key Required.)

**Data Limitations**

Time limitation of the dataset used for this analysis is as per below;
- Dataset is only showing information from December 2009 to the end of 2011.
- Data is only from the UK from an unknown wholesaler, restricting deeper data analysis.
- Customer information is limited to just a customer ID, restricting gender, age or demographic analysis.
- Geographic information was limited to country, which meant we could only look at country vs country.
- Finding the impacts of returns and refunds against the total sales and volume information. 

**Conclusion**

There was no particular correlation between time of day or day of the week
Time of year had a slight correlation with an increase sales 
There is a slight correlation with an increase in volume for a cheaper price 
We believe this is mostly because Customers for a wholesaler are more likely to be commercial, which means there is going to be larger amount of purchases during working hours and as a result of stocktake. 

**Further considerations**

- Obtain data including detailed information such as discounts, refunds, and specials that may be applied, this would allow for understanding if a loyalty program or sales is a better way to increase profitability. 

- Obtain data including cost and profitability so we can find other inefficiencies in sales to match the market. 

- Obtain more data that gives a more detailed breakdown on customers, from Commercial vs Private, as well as age, gender or location, rather than just Country and Customer ID.

"The End"
