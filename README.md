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

 select count(empname) count  ,dept_name from employee_info group by dept_name;

