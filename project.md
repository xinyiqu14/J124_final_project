# J124 Final Project
**@Xinyi Qu**

## Question 1 How are student academic outcomes distributed?  

### Data Analysis Process:
1. Created a pivot table for the student academic outcome.
2. Filter out the missing values (blanks)
3. Calculated the percentage of each category using the formula B2/B5, for example, the percentage of students who dropped out = number of dropout / total number
4. Change the data format into percentage.

![Target Summary](./Q1/Q1.1.png)

[![Distribution of Students in Three Categories for academic success](./Q1/Q1.2.png 'Distribution of Students in Three Categories for academic success')](https://www.datawrapper.de/_/JgfGm/)




## Question 2 How student academic outcomes differed by gender? 

### Data Analysis Process:
1. Created a pivot table for the student academic outcome and gender.
2. Calculated the percentage of each category using the formula B3/E3, for example, the percentage of woman who dropped out = number of female who dropped out / number of total female
3. Change the data format into percentage.

![Target Summary](./Q2/Q2.1.pic.jpg)

[![Student academic outcomes group by gender](./Q2/Q2.2.pic.jpg 'Student academic outcomes group by gender')](https://www.datawrapper.de/_/1ZTg5/)


## Question 3 How student academic outcomes influenced by macroeconomic performance?

### Data Analysis Process:
1. Generated a new dummy variable to label the macroeconomic performance: 
    1. Added a new column with a copy of the “GDP” variable 
    2. Filter by condition
    3. When data is greater than zero, replace to positive growth
    4. When data is less than zero, replace to negative growth
2. Created a pivot table for the student academic outcome and macroeconomic performance.
3. Calculated the percentage of each category using the formula B3/E3, for example, the percentage of dropout when the economy experiences positive GDP growth = number of dropout / number of total sample in positive economic growth
4. Change the data format into percentage.


![Target Summary](./Q3/Q3.1.pic.jpg)
[![Student academic outcomes group by macroeconomics performance](./Q3/Q3.2.pic.jpg 'Student academic outcomes group by macroeconomics performance')](https://www.datawrapper.de/_/8nJS9/)

