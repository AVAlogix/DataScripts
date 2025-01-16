# SQL Challenges for Beginners

This repository contains the solutions for **10 SQL Code Challenges for Beginners** provided by **Stephan Miller** on Codecademy. The challenges are designed to help new learners practice and improve their SQL skills. 
These challenges are meant to provide a hands-on approach to common SQL operations such as table creation, data insertion, querying, and using different SQL functions.

Website: https://www.codecademy.com/resources/blog/sql-code-challenges-for-beginners/

## Challenge Overview

The following challenges were completed as part of this tutorial:

1. **Arithmetic Negation Operator**: Using the negation operator to return the opposite of the values in a column.
2. **Filtering Positive Revenue**: Filtering data based on conditions such as revenue being greater than or equal to zero.
3. **Calculating Century from Year**: Using the `CEIL` function to calculate the century of a given year.
4. **Identifying Odd and Even Numbers**: Using the modulo operator to categorize numbers as odd or even.
5. **Counting Ages**: Using `COUNT` to aggregate and group data by age.
6. **Creating Greetings**: Using string concatenation to generate personalized greetings.
7. **Top 5 Products by Sales**: Sorting data to display the top 5 records based on a column, like sales.
8. **Filtering Countries**: Using `WHERE` and `NOT IN` to filter data based on multiple conditions.
9. **Distinct Ages**: Using `DISTINCT` to find unique values in a column and sorting the results.
10. **Calculating Total Age**: Using the `SUM` function to calculate the total of a numeric column.

## Tools Used

- **MySQL**: All solutions were tested and executed using MySQL, which is a widely used relational database management system. The queries in this repository are written in MySQL syntax and should work with MySQL databases.

## How to Run the SQL Queries

1. Install **MySQL** on your system or use an online MySQL service.
2. Clone or download this repository.
3. Open your MySQL environment or terminal and connect to your database.
4. Create a new database or use an existing one where you want to test these queries.
5. Copy and paste each SQL query into the MySQL command line interface or a MySQL client (such as MySQL Workbench) to execute.

## Challenge Solutions
Each challenge solution is stored in individual SQL files within this repository. You will find a detailed SQL query for each challenge, including table creation, data insertion, and queries to achieve the required task.

The challenges include common SQL operations such as:

Table creation using the CREATE TABLE statement.
Inserting data using the INSERT INTO statement.
Querying data with SELECT.
Using SQL functions like SUM(), CEIL(), COUNT(), and CONCAT().
Filtering data using WHERE, GROUP BY, and ORDER BY.
Conditional logic with CASE WHEN.
Challenge Website
You can access the original challenges provided by Codecademy by visiting their website:  https://www.codecademy.com/resources/blog/sql-code-challenges-for-beginners/

Contributing
If you have any suggestions, improvements, or corrections, feel free to create a pull request. Contributions are welcome!

License
This repository is licensed under the MIT License. See the LICENSE file for more details.


### Key Points:
- **Repository Purpose**: The README gives a brief overview of what the repository is about—solving SQL challenges for beginners.
- **Details on SQL Operations**: It mentions the specific SQL operations covered in the challenges, making it clear to new learners what they will be practicing.
- **Instructions for Running Queries**: Simple instructions on how to run the SQL queries.
- **Challenge Website**: Provides a link to the original website where the challenges are hosted (Codecademy).
- **Contributing**: Encourages contributions from others.
- **License**: Mention the license under which the repository is shared (MIT License in this case).

### Example of Creating a Database and Running the Queries:

```sql
-- Create a new database
CREATE DATABASE sql_challenges;

-- Use the created database
USE sql_challenges;

-- Copy and paste the challenges here to run them
