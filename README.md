# Global Super Store Sales Analysis

## Author

- Vishwjeet Singh chauhan [@vishwjeet14](https://github.com/vishwjeet14)

## Introduction

* This README describes work done on the Global Super Store data set for the Fundamentals of Data Analysis module assessment due 22 April 2022. Resources used include Power-BI.

* To view this file, download it from this repository or click link given below in read me file.

* The Global Super Store data set is downloaded from kaggle. It contain to Files one is  Excel. It contain Three tables and the Tables are related to each other with diffrent attributes.

* I have tried to structure this README so that they have corresponding sections. I will endeavour to have this README summarize the work of the notebook and, hopefully, complement the analyses done there.

## Tool Used in Data Analysis

![alt text](https://github.com/vishwjeet14/Global-Market-Sales-Analysis/blob/main/Pictures/power-bi-microsoft-logo-E4FC8DE4A9-seeklogo.com.png)

## Description of the data set

The data in the Global Super Store data set contains 3 tables (Order, Return, People) Order table contain 51291 rows and 24 columns (Row ID,	Order ID	,Order Date,	Ship Date	,Ship Mode	,Customer ID	,Customer Name	,Segment	,Postal Code	,City	,State	,Country	,Region	,Market	,Product ID	,Category	,Sub-Category,	Product Name	, Sales	Quantity, Discount,	Profit,	Shipping, Cost,	Order ,Priority) , Return table contain 1080 rows and  3 columns (Returned,	Order, ID,	Region) , People table contain 24 rows and 2 columns (Person,	Region).

## Data Cleaning Process

Data cleansing or data cleaning is the process of detecting and correcting corrupt or inaccurate records from a record set, table, or database and refers to identifying incomplete, incorrect, inaccurate or irrelevant parts of the data and then replacing, modifying, or deleting the dirty or coarse data.

Power Query Editor has an incredible amount of features that are dedicated to helping you clean and prepare your data for analysis. You will learn how to simplify a complicated model, change data types, rename objects, and pivot data. You will also learn how to profile columns so that you know which columns have the valuable data that you’re seeking for deeper analytics.

**Acoording to Data here are some step for data cleaning**

* Header of Tables is misplace so we use first row as header function.

![alt text](https://github.com/vishwjeet14/Global-Market-Sales-Analysis/blob/main/Pictures/firstrowheader1.png)
![alt text](https://github.com/vishwjeet14/Global-Market-Sales-Analysis/blob/main/Pictures/first%20row%20as%20a%20header2.png)
![alt text](https://github.com/vishwjeet14/Global-Market-Sales-Analysis/blob/main/Pictures/firstrow%20as%20a%20header.png)

* Order table has a column name postal code, it contain 81% data are missing so we romove this column.

![alt text](https://github.com/vishwjeet14/Global-Market-Sales-Analysis/blob/main/Pictures/postalcode%20null.png)

* We are making new column with called delivery days with the help of ( delivery date - order date ) which give the delivery time of product in days. 

![alt text](https://github.com/vishwjeet14/Global-Market-Sales-Analysis/blob/main/Pictures/delivery%20days%20new%20column.png)

## Dashboard 

link - https://app.powerbi.com/links/8fTBdrqBwu?ctid=e9f22aae-f6f4-40c6-afed-460a4fe1d423&pbi_source=linkShare

![alt text](https://github.com/vishwjeet14/Global-Market-Sales-Analysis/blob/main/Pictures/dashboard.png)

## Conclusion

* Total sales of Global super stores over the four year from 2012 to 2016 is 12.64 million USD.
* Average delivery days is 4.
* Total order over the four year is 178.31 thousand.
* Out of the total order only 1079 Order is returned which is arround 0.1%.
* Asia is the the top market of the global super store and africa is least performance market.
* Half of the buisness arround 51% comes from consumer segment customer.
* Top 10 Customer is Tamar chand, Raymond buch, sajit chand, hunter, bill, harry, susan, mike, adrian, tom.
* Top 5 product is canaon image class200 advance copier, cisco smart phone, motorola smart phone, hover stove, saunder classic bookcase.

## Feedback

If you have any feedback, please reach out to us at vishc70@gmail.com
