**Database Server:** Within the database server we can create different databases. These databases are self-contained sort 
  of silos of information. They have nothing to do one another.

**Command to show databases:** `show databases;`
**Create new databases:** `CREATE DATABASE <database_name>;`  Ex- CREATE DATABASE pet_store;
- we can use both uppercase or lowercase for sql queries.

**Dropping databases:** This will remove a database entirely and all of its contents.
- `drop database <database_name>;`

**Use databases:** Selecting to database to work inside.
- `use <database_name>;`
- To see which database we are working in `select database();'

**Tables:**
- Tables hold the data. a collection of related data held in a structured format within a database.
- Databases are made up of lots of tables.

**Create a new Table:**
- `CREATE TABLE <table_name> (<column_name> <data_type>, <column_name> <data_type>);`
- Ex: CREATE TABLE cats ( name VARCHAR(100), age INT);
- TO see tables list in a database `show tables;`
- To see column names of a table we have to use `show columns from <table_name>;` or `describe cats; or desc cats;`

**Delete Tables:**
- `drop table <table_name>;`

**Comments:** -- use two hyphens to comment before any lines.
