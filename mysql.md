# to run xampp mysql server in ubuntu
~~~bash
sudo /opt/lampp/lampp start
~~~

# to login into mysql
~~~bash
mysql -uroot -p
~~~

# crate a database
~~~sql
CREATE DATABASE <dbname>;
~~~
# to see all databases
~~~sql
SHOW DATABASES;
~~~
# database use  
~~~sql
USE <dbname>
~~~

# Table create
~~~sql
CREATE TABLE EMPLOYEES(
  id INT(11) AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(30) NOT NULL,
  email VARCHAR(30)
);
~~~

# To listing tables
~~~sql
SHOW TABLES;
~~~

# To know the table structure
~~~sql
DESCRIBE <TABLENAME>
~~~

# to insert a row in a table
~~~sql
INSERT INTO <TABLENAME> (column1, column2) VALUES('column1value', 'column2value');
~~~

# to retrieve data from table

~~~sql
SELECT <columnName>, <columnName> FROM <tableName>
SELECT * FROM <tableName>
~~~

# to update row from table
~~~sql
UPDATE <tableName> SET <column>="value" WHERE <columnName>='value'
~~~
# to delete row from table
~~~sql
DELETE FROM <tableName> where <columnName>='value'
~~~

people 
id name email