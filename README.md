![](Deforestation.png)

# Introduction
This is a SQL-project whic focuses on studing defprestation across different countries in different regions(continent) between the year 1990 amd 2016. It includes three tables 

The forest_area table
![](forest_area.png)

 The Land_area table 
 ![](Land_area.png)
  
  The region table
  ![](region.png)

  # Problem Statement
Question 1: What are the total number of countries involved in deforestation? 

Question 2: Show the income groups of countries having total area ranging from 75,000 to 150,000 square meter?

Question 3: Calculate average area in square miles for countries in the 'upper middle income region'. Compare the result with the rest of the income categories.

Question 4: Determine the total forest area in square km for countries in the 'high income' group. Compare result with the rest of the income categories.

Question 5: Show countries from each region(continent) having the highest total forest areas. 

# Tool and Skills Demostrated
1) T-SQL
2) Data Cleaning and Transformation
3) Sub_Query
4) Window Functions

# Data Cleaning and Transformation
Step 1; I Created Database 

CODE;

`CREATE DATABASE SQL_PROJECT1;
USE SQL_PROJECT1;`

Step 2; I Imported the Csv file
![](SQL_PROJECT_1.png)

Step 3; I Loaded all files to ensure they are all imported

Code Used
`SELECT * FROM Forest_Area;
SELECT * FROM Land_Area;
SELECT * FROM Region;`
![](SQL_PROJECT_2.png)

Step 4; I checked all tables for null values
Null values were found in the FOREST_AREA_SQKM coloumn in the Forest_area Table
![](NULL_FOREST_AREA_SQKM.png)


