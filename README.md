# Crowdfunding_ETL

### Members:
Yu-hsi Chen \
Tuan Hoang \
Daniel Corral \
Brian Lee \
Nicholas Dao \
Quoc Tran \
Cristian Jung

## Project Description:
In this mini project, the goal was to work in groups to practice building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the provided data. The transformed data would then be exported into the required CSV files that would be utilized to create an ERD, a table schema, and uploaded into a Postgres database.  

### Breakdown of Tasks:
- Create the Category and Subcategory DataFrames
	- Done by using the Pandas 'str.split' method, NumPy arrays, and list comprehension to separate the 'category & subcategory' column and its values	
- Create the Campaign DataFrame
	- Renamed columns, converted them into the desired datatypes (integers to float/datetime), and dropped unwanted columns
- Create the Contacts DataFrame
	- Given two options, we chose to use regex to extract and split the data from the given Excel sheet into a new dataframe that allows us to view each person's contact IDs, first name, last name, and their respective emails
	- This final dataframe would then be exported into a CSV file
- Create the Crowdfunding Database
	- With the finished CSV files, we created an ERD and a subsequent table schema which was then used to create our final database 
