# sql_practice

sql -->structured query language

how to create database in mysql:
create database dabase name

switch to/use database

use database name

query to find list of tables in sql

show tables

syntax to create table in my sql

create table employee_info(empid int,empName varchar(255),dept_name varchar(255),salary int)

how to alter column name in table:

alter table employee_info rename column original_column_name to new_column_name

max sal:
select max(salary) from employee_info;

min sal

select max(salary) from employee_info;

select min(salary) from  employee_info;

mysql> insert into employee_info values(3,'Chandu','admin',1000000);

 select count(empname) count  ,dept_name from employee_info group by dept_name;
 
 mysql> select empName  Employee_Name from employee_info;
 
 mysql> select count(empname)  ,dept_name from employee_info group by dept_name;
 
 mysql> select count(empname) count  ,dept_name from employee_info group by dept_name;
 
 how to find nth max salary 
 
 
 select * from employee_info order by salary desc limit offset(n-1),limit
 
  select * from employee_info order by salary desc limit 2,1
  
 update employee_info set empName = 'test' where empid=1
 
 joins:
 self join
 
 inner join
 
 left outer join
 right outer join
 full join

