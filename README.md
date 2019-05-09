# sql-learning


https://www.youtube.com/watch?v=9ylj9NR0Lcg



https://www.udemy.com/courses/search/?src=ukw&q=sql

cheat sheet for mysql

https://gist.github.com/bradtraversy/c831baaad44343cc945e76c2e30927b3


distinct key word will return a unique value on the table 

where key word requires single quotes when comparing data
eg Select * from emp where job = 'MANAGER'

AND key word lets you concat statements together

also after using the first WHERE state you MUST ust AND after to add more cases for to the first statement. 

SQL or condition
The SQL AND condition and OR condition can be combined to test for multiple conditions in a SELECT, INSERT, UPDATE, or DELETE statement. When combining these conditions, it is important to use parentheses so that the database knows what order to evaluate each condition.
https://apex.oracle.com/pls/apex/f?p=4500:1003:101201220576256::NO:::

all operators same as JS

IN operator 

The IN operator allows you to specify multiple values in a WHERE clause.

The IN operator is a shorthand for multiple OR conditions.


SELECT column_name(s)
FROM table_name
WHERE column_name IN (value1, value2, ...);

() in sql
This is basic order of operations. The parentheses mean that everything is tested before anything else is tested. The value returned after evaluating the items in the parentheses will then be used to evaluate the rest. Since AND takes precedence over OR, the parentheses make SQL evaluate the ORs first.

LIKE

The LIKE operator is used in a WHERE clause to search for a specified pattern in a column.

There are two wildcards often used in conjunction with the LIKE operator:

% - The percent sign represents zero, one, or multiple characters
_ - The underscore represents a single character


|| concat

|| operator concatenates one or more strings into a single string in Oracle.

Quick Example:

   -- Concatenate strings 'New ' and 'York'
   SELECT 'New ' || 'York' FROM dual;
   -- Result: New York

   -- TEST
   SELECT ENAME || ' MAKES $' || SAL || ' PER MONTH' AS "TEST"
 FROM EMP;


 The ORDER BY keyword is used to sort the result-set in ascending or descending order. The ORDER BY keyword sorts the records in ascending order by default. To sort the records in descending order, use the DESC keyword.

 The DUAL is special one row, one column table present by default in all Oracle databases. The owner of DUAL is SYS (SYS owns the data dictionary, therefore DUAL is part of the data dictionary.) but DUAL can be accessed by every user. The table has a single VARCHAR2(1) column called DUMMY that has a value of 'X'. MySQL allows DUAL to be specified as a table in queries that do not need data from any tables. In SQL Server DUAL table does not exist, but you could create one.
The DUAL table was created by Charles Weiss of Oracle corporation to provide a table for joining in internal views.