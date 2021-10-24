# SQL

## In a SQL table, what is the difference between information in a row and information in a column?
Columns contain the column name, data type, and any other attributes for the column. Rows contain the records or data for the columns.

## Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
CREATE TABLE IF NOT EXISTS characters(
  id int NOT NULL PRIMARY KEY AUTO_INCREMENT comment 'primary key',
  name varchar(255) NOT NULL,
  age varchar(255) NOT NULL,
  description varchar(255) NOT NULL,
) default charset utf8 comment '';


## What is the difference between the following statements:

    DELETE FROM table_name;
    DROP TABLE table_name;

    Delete from table is just deleting a row, drop table is completely dropping the whole table and all it's memory.

    afternoon challenge: https://github.com/hannahmilam/KnightsTale
