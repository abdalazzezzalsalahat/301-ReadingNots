

#  SQL
![img](https://techskill.sg/wp-content/uploads/2020/06/SQL-server.jpg)
- stands for Structured Query Language
- SQL is used to communicate with a database.
- it is the standard language for relational database management systems
- SQL statements are used to perform tasks such as update data on a database, or retrieve data from a database
- Some common relational database management systems that use SQL are: 
    1. Oracle
    2. Sybase
    3. Microsoft SQL Server
    4. Access
    5. Ingres
- SQL commands such as `Select`, `Insert`, `Update`, `Delete`, `Create`, and `Drop` can be used to accomplish almost everything that one needs to do with a database.


## Table

- A relational database system contains one or more objects called tables.

## Selecting Data
- The select statement is used to query the database and retrieve selected data that match the criteria that you specify. Here is the format of a simple select statement:
```
 - select "column1"
  [,"column2",etc] 
  from "tablename"
  [where "condition"];
  [] = optional
```
## Creating Tables
- The create table statement is used to create a new table. Here is the format of a simple create table statement:
```
create table "tablename"
("column1" "data type",
 "column2" "data type",
 "column3" "data type");
```
Format of create table if you were to use optional constraints:
```
create table "tablename"
("column1" "data type" 
         [constraint],
 "column2" "data type" 
         [constraint],
 "column3" "data type" 
        [constraint]);
 [ ] = optional
```
## Inserting into a Table
- The insert statement is used to insert or add a row of data into the table.
```
insert into "tablename"
 (first_column,...last_column)
  values (first_value,...last_value);
```
## Updating Records
- The update statement is used to update or change records that match a specified criteria. This is accomplished by carefully constructing a where clause.
```
update "tablename"
set "columnname" = 
    "newvalue"
 [,"nextcolumn" = 
   "newvalue2"...]
where "columnname" 
  OPERATOR "value" 
 [and|or "column" 
  OPERATOR "value"];
[] = optional
```
## Deleting Records
- The delete statement is used to delete records or rows from the table.

```
- delete from "tablename"
where "columnname" 
  OPERATOR "value" 
[and|or "column" 
  OPERATOR "value"];

[ ] = optional
```

## Drop a Table

- `drop table "tablename"`

![img](https://www.sololearn.com/certificates/course/en/20745451/1060/landscape/png)