# My-Third-Excel-data-analysis-project
## Introduction
This project involves advance functions calculations in excel from previous large data set used in project 2

## Aim of Project
To be able to calculate using the sales data the following
- The average revenue generated from each sale of ‘Paseo’
- The number of sales made in the Government and Midmarket segment
- The total revenue generated from the sales of ‘Montana’ in Canada
- In which Country, Segment and Month was the highest unit of goods sold?
- What is the total profit made in December?
To put to test most advanced calculation used in analysing large data

# Procedure
To get this values extracted from the large data set, the following advanced calculations will be employed. They include **VLOOKUP**,**SUMIF**, **SUMIFS** and **AVERAGEIF**
1. The average revenue generated from each sale of ‘Paseo’ is gotten by running the **AVERAGEIF** function on the sales column, which gives  **$163,421.50**

2. To get the number of sales made in Government and Midmarket segment, you apply the SUMIFS function on the sales column, with respect to the Government column, and another with respect to the Midmarket. This calculates the following values for Government **52,504,260.67**, and Midmarket **2,381,883.08**, which is added to give **$54,886,143.75**

3. To acquire The total revenue generated from the sales of ‘Montana’ in Canada, we apply the **SUMIFS** function for sales with respect to Montana and Canada, which gives us **$2,711,919.03**

4. To answer this question 'In which Country, Segment and Month was the highest unit of goods sold?'
- First calculate and obtain the highest unit sold, using the **MAX** function on the unit column. This returns the value **4492.5**
- Then apply the VLOOKUP function to obtain the month where that value was obtained, which returned **APRIL**
- Apply VLOOKUP function again for the country. The country column has to be placed in front of our source value in the table to get the result. This returned **United States of America**

5. For total profit made in december, we employ the SUMIF function on the month column, against the profit column, to give  **$2,717,329.98**

# CONCLUSION
I was able to combine basic and advanced function in analysing my data. I also saw the importance of creating a sub-table where data analysed from the larger table can be kept for reference. This made my job easier and neat 



