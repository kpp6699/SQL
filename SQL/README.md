SQL Data Analysis Project 
Business related questions for management

1
Find the average salary of the male and female employees in each department.

2
Find the lowest department number encountered in the 'dept_emp' table. Then, find the highest
department number.

3

Obtain a table containing the following three fields for all individuals whose employee number is not
greater than 10040:
- employee number
- the lowest department number among the departments where the employee has worked in (Hint: use
a subquery to retrieve this value from the 'dept_emp' table)
- assign '110022' as 'manager' to all individuals whose employee number is lower than or equal to 10020,
and '110039' to those whose number is between 10021 and 10040 inclusive.

4
Retrieve a list of all employees that have been hired in 2000.

5
Retrieve a list of all employees from the ‘titles’ table who are engineers.
Repeat the exercise, this time retrieving a list of all employees from the ‘titles’ table who are senior
engineers.


6
Create a procedure that asks you to insert an employee number and that will obtain an output containing
the same number, as well as the number and name of the last department the employee has worked in.
Finally, call the procedure for employee number 10010.

7
How many contracts have been registered in the ‘salaries’ table with duration of more than one year and
of value higher than or equal to $100,000?

8
Create a trigger that checks if the hire date of an employee is higher than the current date. If true, set the
hire date to equal the current date. Format the output appropriately (YY-mm-dd).

9
Define a function that retrieves the largest contract salary value of an employee. Apply it to employee
number 11356.

10
Based on the previous example, you can now try to create a function that accepts also a second parameter which would be a character sequence. 
Evaluate if its value is 'min' or 'max' and based on that retrieve either the lowest or the highest salary (using the same logic and code 
from Exercise 9). If this value is a string value different from ‘min’ or ‘max’, then the output of the function should return 
the difference between the highest and the lowest salary.
