# Pewlett Hackard Analysis

## Overview of Project

The purpose of this project is to determine the number of retiring employees per title, and identify employees who are eligible to participate in a mentorship program by using SQL. In order to complete this project, we need to create two tables. One is creating a Retirement Titles table that holds all the titles of employees who were born between January 1, 1952 and December 31, 1955. Another one is creating a mentorship-eligibility table that holds the current employees who were born between January 1, 1965 and December 31, 1965.


## Results
1. According to the retirment_titles table, we are able to find every eligible for retirement employee and how long they have worked at each position in the company.

2. Employees who are Senior Engineer have the highest amount of retiring individuals. Only 2 Managers are in the retiring_titles table.

3. Based on the retiring_titles table we created, we can find that majority of the employees who are in the retirement ages are Senior level employees, over 70% (50842/72458 =70.17%)are Senior Engineer and Senior Staff.

![retiring_titles](https://github.com/ningci0723/Pewlett-Hackard-Analysis/blob/main/Resources/retiring_titles.png)

4. From the mentorship_eligibilty table, we can find that 1,549 employees who are eligible to participate in a mentorship program.

![mentorship_eligibilty](https://github.com/ningci0723/Pewlett-Hackard-Analysis/blob/main/Resources/mentorship.png)


## Conclusion
### Questions
1. How many roles will need to be filled as the "silver tsunami" begins to make an impact?
There are 72,458 roles needed to be filed as the "silver tsunami" begins to make an impact, please see below for the reference.
![retiring_titles](https://github.com/ningci0723/Pewlett-Hackard-Analysis/blob/main/Resources/retiring_titles.png)

2. Are there enough qualified, retirement-ready employees in the departments to mentor the next generation of Pewlett Hackard employees?
No, there are only 1,549 employees who are eligible to participate in a mentorship program.

### Additional Queries or Tables
 We can count the numbers of qualified mentor by using group by titles based on the mentorship_eligibilty table and we can find the below result.
![mentor by titles](https://github.com/ningci0723/Pewlett-Hackard-Analysis/blob/main/Resources/mentor%20by%20title.png)
Based on the above results, we can find that totaling number of qualified mentors are only 1,549. One possible reason may include that we only consider the employees whose birth dates are between January 1, 1965 and December 31, 1965. Assuming that if we increase the data area, we deem that the qualified mentors are employees whose birth dates are between January 1, 1960 and December 31, 1970, then we can get 93,756 qualified mentors.
![new mentor by titles](https://github.com/ningci0723/Pewlett-Hackard-Analysis/blob/main/Resources/new%20mentors%20by%20titles.png)
