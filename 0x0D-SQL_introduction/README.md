
amirgambo
/
alx-higher_level_programming
Public
Code
Issues
Pull requests
Actions
Projects
Security
Insights
Directory actionsMore options
Breadcrumbsalx-higher_level_programming
/0x0D-SQL_introduction/
Latest commit
amirgambo
amirgambo
3 months ago
History
Breadcrumbsalx-higher_level_programming
/0x0D-SQL_introduction/
Folders and files
Name	Last commit date
parent directory
..
0-list_databases.sql
(File)
3 months ago
1-create_database_if_missing.sql
(File)
3 months ago
10-top_score.sql
(File)
3 months ago
100-move_to_utf8.sql
(File)
3 months ago
101-avg_temperatures.sql
(File)
3 months ago
102-top_city.sql
(File)
3 months ago
103-max_state.sql
(File)
3 months ago
11-best_score.sql
(File)
3 months ago
12-no_cheating.sql
(File)
3 months ago
13-change_class.sql
(File)
3 months ago
14-average.sql
(File)
3 months ago
15-groups.sql
(File)
3 months ago
16-no_link.sql
(File)
3 months ago
2-remove_database.sql
(File)
3 months ago
3-list_tables.sql
(File)
3 months ago
4-first_table.sql
(File)
3 months ago
5-full_table.sql
(File)
3 months ago
6-list_values.sql
(File)
3 months ago
7-insert_value.sql
(File)
3 months ago
8-count_89.sql
(File)
3 months ago
9-full_creation.sql
(File)
3 months ago
README.md
(File)
3 months ago
temperatures.sql
(File)
3 months ago
README.md
https://github.com/sammykingx/alx-higher_level_programming/blob/master/0x0D-SQL_introduction/README.md#mysql

0x0D. SQL - Introduction

MANDATORY TASKS

Write a script that lists all databases of your MySQL server.
Write a script that creates the database hbtn_0c_0 in your MySQL server.
If the database hbtn_0c_0 already exists, your script should not fail You are not allowed to use the SELECT or SHOW statements

Write a script that deletes the database hbtn_0c_0 in your MySQL server.
If the database hbtn_0c_0 doesn’t exist, your script should not fail You are not allowed to use the SELECT or SHOW statements

Write a script that lists all the tables of a database in your MySQL server.
The database name will be passed as argument of mysql command (in the following example: mysql is the name of the database)

Write a script that creates a table called first_table in the current database in your MySQL server.
first_table description: id INT name VARCHAR(256) The database name will be passed as an argument of the mysql command If the table first_table already exists, your script should not fail You are not allowed to use the SELECT or SHOW statements

Write a script that prints the full description of the table first_table from the database hbtn_0c_0 in your MySQL server.
The database name will be passed as an argument of the mysql command You are not allowed to use the DESCRIBE or EXPLAIN statements

Write a script that lists all rows of the table first_table from the database hbtn_0c_0 in your MySQL server.
All fields should be printed The database name will be passed as an argument of the mysql command

Write a script that inserts a new row in the table first_table (database hbtn_0c_0) in your MySQL server.
New row: id = 89 name = Best School The database name will be passed as an argument of the mysql command

Write a script that displays the number of records with id = 89 in the table first_table of the database hbtn_0c_0 in your MySQL server.
The database name will be passed as an argument of the mysql command

Write a script that creates a table second_table in the database hbtn_0c_0 in your MySQL server and add multiples rows.
second_table description: id INT name VARCHAR(256) score INT The database name will be passed as an argument to the mysql command If the table second_table already exists, your script should not fail You are not allowed to use the SELECT and SHOW statements Your script should create these records: id = 1, name = “John”, score = 10 id = 2, name = “Alex”, score = 3 id = 3, name = “Bob”, score = 14 id = 4, name = “George”, score = 8

Write a script that lists all records of the table second_table of the database hbtn_0c_0 in your MySQL server.
Results should display both the score and the name (in this order) Records should be ordered by score (top first) The database name will be passed as an argument of the mysql command

Write a script that lists all records with a score >= 10 in the table second_table of the database hbtn_0c_0 in your MySQL server.
Results should display both the score and the name (in this order) Records should be ordered by score (top first) The database name will be passed as an argument of the mysql command

Write a script that updates the score of Bob to 10 in the table second_table.
You are not allowed to use Bob’s id value, only the name field The database name will be passed as an argument of the mysql command

Write a script that removes all records with a score <= 5 in the table second_table of the database hbtn_0c_0 in your MySQL server.
The database name will be passed as an argument of the mysql command

Write a script that computes the score average of all records in the table second_table of the database hbtn_0c_0 in your MySQL server.
The result column name should be average The database name will be passed as an argument of the mysql command

Write a script that lists the number of records with the same score in the table second_table of the database hbtn_0c_0 in your MySQL server.
The result should display: the score the number of records for this score with the label number The list should be sorted by the number of records (descending) The database name will be passed as an argument to the mysql command

Write a script that lists all records of the table second_table of the database hbtn_0c_0 in your MySQL server.
Don’t list rows without a name value Results should display the score and the name (in this order) Records should be listed by descending score The database name will be passed as an argument to the mysql command

ADVANCED TASKS

Write a script that converts hbtn_0c_0 database to UTF8 (utf8mb4, collate utf8mb4_unicode_ci) in your MySQL server.
You need to convert all of the following to UTF8:

Database hbtn_0c_0 Table first_table Field name in first_table

Import in hbtn_0c_0 database this table dump: download
Write a script that displays the average temperature (Fahrenheit) by city ordered by temperature (descending).

Import in hbtn_0c_0 database this table dump: download (same as Temperatures #0)
Write a script that displays the top 3 of cities temperature during July and August ordered by temperature (descending)

Import in hbtn_0c_0 database this table dump: download (same as Temperatures #0)
Write a script that displays the max temperature of each state (ordered by State name).