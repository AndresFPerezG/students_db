# Computer Scince students Database
Course: I created a Bash script that uses SQL to enter information about computer science students into PostgreSQL.

# Postgres commands:
1. Enter to Postgres interactive terminal: psql --username=[username] --dbname=[dbname]
2. List the existing databases: \l
3. Create a new db: CREATE DATABASE [db_name];
4. Connect to a database: \c [db_name]
5. Create a new table: CREATE TABLE [table_name](); e.g, => CREATE TABLE students();
6. List tables: \d
7. Add a foreign key: ALTER TABLE <table_name> ADD FOREIGN KEY(<column_name>) REFERENCES <referenced_table_name>(<referenced_column_name>);



