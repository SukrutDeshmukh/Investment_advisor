# Investment_advisor
![8432](https://github.com/SukrutDeshmukh/Investment_advisor/assets/127339353/9c590687-0555-4e05-ac8e-0b0ecb59ea61)

The project is primarily supported by two datasets.BSE500 data is included in one dataset, while the income and expenses of random users is included in another dataset.The objective of this project was to use some fundamental knowledge of the stock market and, based on that, to create several levels of investment profiles that users could select, and in return, receive stock recommendations on which they could invest using the money they had available.

Steps involved in building project.

Step 1 - Understanding the data which is present Gsheets.
Step 2 - performing data cleaning using Gsheets tools.
Step 3 - Linking Gsheet with python code with the help of Google cloud Api
Step 4 - Using Gspread library for extracting details from sheets,cells and for uploading changes on sheets again after performing operations.
Step 5 - Getting both the data sheets in python with the help gspread for performing further opeartions using pandas library.
Step 6 - Creating four profiles for user and applying below conditions on the BSE500 data.

Steps   High Risk Taking	Risk Taking	Moderate Risk
Taking
 

Low Risk Taking
 

 
Make a new column in Gsheet 1 named “Delta”
1	and populate it with (52 Week High - price)/(52 week High)
 
Make a new column in Gsheet 1 named “Delta” and populate it with (52 Week High - price)/(52 week High)
 
Make a new column in Gsheet 1 named “Delta” and populate it with (52 Week High - price)/(52 week High)
 
Make a new column in Gsheet 1 named “Delta” and populate it with (52 Week High - price)/(52 week High)
 

 
Filter out those
2	where Delta column is positive
(>0)

Filter out those
3	whose Market
Cap(Cr) is lesser
 
Filter out those where Delta column is positive (>0)

Filter out those whose Market Cap(Cr) lies
 
Filter out those where Delta column is positive (>0)

Filter out those whose Market Cap(Cr) is
 
Filter out those where Delta column is positive (>0)

Filter out those whose Market Cap(Cr) is greater
 
than 2000
 
between 2000 and between 5000 and than 15000
 


Filter out the column where 10-
4	Year Return(%) is
lesser than 8
 
5000

Filter out the column where 10- Year Return(%) is between 8 and 15
 
15000

Filter out the column where 10- Year Return(%) is between than 15
and 20
 


Filter out the column where 10- Year Return(%) is greater than 20
 

 
Sort the column
named Dividend Per Share in
5	descending order
and pick the 5 highest value
 
Sort the column named Dividend Per Share in descending order and pick the 5 highest value
 
Sort the column named Dividend Per Share in descending order and pick the 5 highest value
 
Sort the column named Dividend Per Share in descending order and pick the 5 highest value

