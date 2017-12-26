# Pandas
Used pandas to query data

1. Select First name, Last name, Address, Country Name (by joining with country table), Sate Name (by joining with state table), City Name (by joining with city table),Mobile, and Designation name (by joining with designation table) of all employees .
2. Select state name and country name and sort the records in ascending order with state name.
3. Select first 3 records from country table in ascending order by country name.
4. Select all employees whose first name starts with letter “a”.
5. Select all employees whose first name ends with letter “a”
6. Select all employees who are inactive.
7. Select first name, last name, middle name of all employees and change the column names to First Name, Last Name, and Middle Name.
8. Print total number of employees.
9. Print total number of employees whose middle name is not null.
10. Select first name, last name, middle name of all employees. If middle name is null change that value to “Not Applicable”.
11. Concatenate first name, middle name, last name of all records in employee table and print.
12. Select all records in employee table and order in ascending direction with country name.
13. Retrieve first 10 records from employee table and order by their first name in ascending direction.
14. Select all record from employee who lives in the cities Dallas, Algiers.
15. Select all employees who lives in the cities that starts with the letter s between A and D.
16. Fetch First name, last name, middle name, Country name, Designation name and DOB within a range (e.g.: 1/2/1984 to 1/3/1986).
17. Fetch First name, Last name, middle name, Country name, Designation name and highest salary.
18. Fetch First name, Last name, middle name, Country name, Designation name and his current salary.
19. Fetch First name, Last name, middle name, Country name, Designation name and his/her highest salary within a range (e.g. : 50000 to 100000).
20. Select first 3 characters of EMP_FIRST_NAME from EMPLOYEE_DETAILS   -- SUBSTRING(COLUMN_NAME,1,3)
21. If there is any letter “A” in Emp_First_Name, replace “A” with “$”.
a. E.g. Francis  Fr$ncis

22. Select EMP_FIRST_NAME ,Joined year, Joined Month name and joined day from 
Employee details table.
E.g.:	First Name	Year      Moth     Day
 Ayodeji	2014	Jan	 5

23. Get employee details from employee details table whose joining year is “2014”.
24. Get employee details from employee table who joined before January 1st 2014
25. Get Designation, total salary spend by the company with respect to each E.g.
Designation Name		Total Salary
Mobile Software Engineer	622100.00

26. Get designation name, no of employees in a designation with respect to a designation from employee details table.
27. Get designation wise average salaries from employee details table and order by Salary ascending.
28. Select no of employees joined with respect to year and month from 
Employee details table.
e.g.:
Joined Year	Joined Month		Number of employees
2013		1			2
29. Select employee from employee details table whose salary is not yet in the salary table.
30. Select first name, sum of salary from employee details and salary table for all employees even if they didn't get salary and set salary amount as 0 for those employees who didn't get salary. 
Hint: use left outer join
31. Select 10 % of current salary from Employee1, 20% of Employee1, 15% of Employee3 and for others 30 % of salary from employee table.
32. Display how many days each employee worked in the company.
33. Select the employee with highest appraisal. (difference of first salary and current salary)
34. Select the employees who have the third highest current salary.
35. Display employee name, and average salary with the help of a user defined function.
