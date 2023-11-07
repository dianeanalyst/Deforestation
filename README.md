# Deforestation
A project is always used to mark the end of each data analysis class. This project on deforestation marks the end of SQL classes in the Data Analysis 3rd Cohort with Victor Somadina.
# Introduction
This project presented opportunities to further use and understand some advanced SQL functions such as the windows functions, common table expressions(CTEs), Joins, Subquerys etc. Three datasets were used to carry out this project, namely Forest Area, Land Area and Regions. All three datasets had some similar columns, these are Country_Name, and Country_Code. 
# Sample Datasets
The image below a return of all the three datasets used in carrying out this project.

![image](https://github.com/dianeanalyst/Deforestation/assets/120665115/49f570e7-ea7d-4b4a-aad7-8b5738be2852)

# Project Questions and Answers
There are 6 questions assigned to be answered in this project.
1. Find the total number of countries involved in deforestation.

![image](https://github.com/dianeanalyst/Deforestation/assets/120665115/c0ed82de-8186-4756-b32d-4ca099da5b2c)
#
2. Show the income groups of countries having total area ranging 75,000 to 150,000.
- To answer this, the Regions and Land Area datasets were joined using the JOIN clause. Also, in narrowing down the selection to the stated range, the BETWEEN operator was used with the WHERE clause.
![image](https://github.com/dianeanalyst/Deforestation/assets/120665115/e651f4e4-e4ea-4194-874d-ead5abe85a97)

3. Retrieve the names of countries that have a forest area greater than the average forest area of all countries in the "High Income" income group.
- I applied a stepwise approach in answering this question. First step was getting the average forest area of all countries uding the AVG operator. Next step was adding the first step as a subquery to the WHERE condition.
![image](https://github.com/dianeanalyst/Deforestation/assets/120665115/75608fe3-0a31-4bf8-a112-9bb1ff8f1058)

5. Calculate the average total area for countries in the "Upper Middle Income" income group. Compare the result with the rest of the income categories. Hint: Calculate the average total area for the 3 other categories.
![image](https://github.com/dianeanalyst/Deforestation/assets/120665115/afd6ccea-9c7e-489b-97bf-6ac6336cc830)

![image](https://github.com/dianeanalyst/Deforestation/assets/120665115/a5ba658b-a22c-4775-b37a-6a076642620b)

5. Determine the total forest area for countries in the "High Income" income group. Also compare with the other income categories.
![image](https://github.com/dianeanalyst/Deforestation/assets/120665115/1f004db0-0ee0-4df5-b997-65c8eacf8525)

6. What area the countries from each region or continent having the highest total forest area?
![image](https://github.com/dianeanalyst/Deforestation/assets/120665115/d67c8e45-f206-4510-83ad-8397785e876d)


