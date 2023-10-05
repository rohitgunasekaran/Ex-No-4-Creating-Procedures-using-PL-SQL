# Ex. No: 4 Creating Procedures using PL/SQL

### AIM: To create a procedure using PL/SQL.

### Steps:
1. Create employee table with following attributes (empid NUMBER, empname VARCHAR(10), dept VARCHAR(10),salary NUMBER);
2. Create a procedure named as insert_employee data.
3. Inside the procdure block, write the query for inserting the values into the employee table.
4. End the procedure.
5. Call the insert_employee data procedure to insert the values into the employee table.
6. Display the employee table

### Program:
```
 delimiter //
create procedure Insert_employee()
    begin
    declare empid int;
    declare empname varchar(10);
    declare dept varchar(10);
    declare salary int;
    insert into employee(empid,empname,dept,salary)values(1,'arun','HR',100000);
    insert into employee(empid,empname,dept,salary)values(2,'varman','glad',50000);
    insert into employee(empid,empname,dept,salary)values(2,'varun','sales',30000);
    -> end;
    -> delimiter//
```
### Output:![image](https://github.com/rohitgunasekaran/Ex-No-4-Creating-Procedures-using-PL-SQL/assets/119404546/9a0a7398-4f63-4381-a6ae-83f029819c08)


### Result: thus the program is succesfully created using PLSQL.
