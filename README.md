# LITA_Class_Documentation
This is where I documented my first project while learning data analysis on Incubator Hub

## Data Analysis Using Excel

Data analysis is a systematic process of inspecting, cleansing, transforming, and modeling data to discover useful information, draw conclusions, and support decision-making. Excel serves as a powerful tool for data analysis due to its diverse functionalities, which facilitate tasks ranging from data cleaning to advanced visualization. 

### Key Components of Data Analysis in Excel

#### 1. Data Cleaning
Data cleaning is a crucial step in the data analysis process, ensuring that the dataset is accurate and consistent. Key techniques learned include:

- *Combining Names*: Merging first and last names into a single full name for easier management.
- *Generating Emails*: Using concatenation functions to create email addresses from first names.
- *Standardizing Formatting*: Applying functions such as PROPER, UPPER, LOWER, and TRIM to clean and format data, improving readability and accuracy.

*Importance*: Properly cleaned data lays the foundation for reliable insights and analyses.

![image](https://github.com/user-attachments/assets/bd7edd13-2881-48a8-a69c-1b3e7b2a86ef)

![image](https://github.com/user-attachments/assets/96b66b81-8692-4efc-b52e-84e04df05247)

![image](https://github.com/user-attachments/assets/096ce4eb-4254-4d7f-a0f5-99958bd676f4)

#### 2. Data Visualization
Data visualization involves representing data in graphical formats to make it easier to understand patterns and insights. Key techniques explored include:

- *Conditional Formatting*: Highlighting specific data points based on conditions to identify trends quickly.
- *Charts and Graphs*: Creating various visual representations of data to communicate findings effectively.
- *Pivot Tables*: Utilizing pivot tables to summarize large datasets, allowing for dynamic filtering, grouping, and the extraction of key insights.

*Insights Gained*:
- Top regions, sales by stores, and revenue breakdowns can be visualized effectively to inform strategic decisions.

![image](https://github.com/user-attachments/assets/fb285a50-39c6-477d-bb49-6c7adb708af2)

![image](https://github.com/user-attachments/assets/374aaa9d-4650-4f02-8434-673c37d39be0)

#### 3. Statistical Calculations
Excel provides a range of functions to perform statistical calculations that inform data analysis. This includes:

- *Total and Average Calculations*: Computing grand totals and averages for various metrics, such as salaries.
- *Identifying Extremes*: Pinpointing the highest, lowest, and specific ranking values within the data.
- *Conditional Statistics*: Using functions to derive metrics based on specific conditions, like total salary by region.

![image](https://github.com/user-attachments/assets/87f87278-8ad0-433e-951e-93bbbf01b7d6)

![image](https://github.com/user-attachments/assets/f057e48c-1266-43c2-bc09-af2c9ad01618)

#### 4. Data Retrieval Techniques
Utilizing Excel functions for efficient data retrieval enhances analysis accuracy. Key methods include:

- *VLOOKUP*: This function was instrumental in retrieving salary components based on employee grade levels, ensuring accurate calculations across departments.
  
*Application*: VLOOKUP simplified the connection between employee data and salary structures, promoting consistency in gross pay calculations.

![image](https://github.com/user-attachments/assets/8e9d9824-3696-47b1-8ae9-da70f7e7e404)

![image](https://github.com/user-attachments/assets/e31c8fc5-df63-44b0-8f1f-aa69984625df)

![image](https://github.com/user-attachments/assets/1dcf6a3a-0b66-45cc-98be-f42d04e63281)

#### 5. Text Extraction and Formatting
Text extraction techniques were employed to make raw data more meaningful. This involved using functions like:

- *LEFT(), MID(), RIGHT()*: To dissect and extract relevant information from text strings.
  
*Outcome*: These functions aided in breaking down complex codes into structured components, facilitating easier analysis.

![image](https://github.com/user-attachments/assets/ead819cd-2964-440e-b87e-c837391cf11a)

![image](https://github.com/user-attachments/assets/a768c62a-e783-4c48-8518-6d463b4015b6)

#### 6. Advanced Data Cleaning and Formatting
In addition to basic data cleaning, advanced techniques were used to ensure data consistency and readability. This included:

- *Using the TRIM function*: Eliminating extra spaces within cells for better formatting.
- *Implementing the LEFT function*: Extracting first names or other relevant data points for clearer data management.

*Impact*: Clean, well-structured data leads to smoother analysis and enhanced accuracy in reporting.

![image](https://github.com/user-attachments/assets/31b6c8a0-8f67-4a2d-8fdb-dcde5bf33f39)

![image](https://github.com/user-attachments/assets/e4fafc08-d67d-4bec-82bb-e5135af39b0d)

![image](https://github.com/user-attachments/assets/a01362c3-ab5f-4b7f-b21d-1bcaf6e32c44)

![image](https://github.com/user-attachments/assets/d498149a-1fc0-4c59-82d7-519dfa1d7999)

#### 7. Unlocking Insights with Pivot Tables
Pivot tables are essential for quickly summarizing and analyzing large data sets. They transform raw data into digestible insights, allowing for easy comparison, filtering, and grouping.

*Key Features*:
- *Summarization*: Use functions like sum, average, or count to get quick statistics.
- *Dynamic Filtering*: Focus on the most relevant data by filtering and sorting.
- *Grouping*: Organize data by categories or date ranges for clearer analysis.

*Insights Gained*: Using pivot tables, it was possible to quickly see key performance metrics, such as top-performing regions and stores.

![image](https://github.com/user-attachments/assets/15b791c7-16aa-41ea-b1e1-67703d245682)

![image](https://github.com/user-attachments/assets/875b3415-1ead-4955-8abb-33cf3ea8f272)

![image](https://github.com/user-attachments/assets/0cc4692d-2f81-4ed6-bba8-2fc12556f373)


## Data Analysis with SQL

Data analysis with SQL involves managing, querying, and manipulating data stored in relational databases. It allows users to derive insights and make informed decisions based on data. Below is a comprehensive overview of key concepts learned during the SQL practice.

### 1. Building Foundations with SQL Tables and Queries

Creating and managing tables is fundamental to database design and management. I practiced creating an *Employee* table with attributes such as names, gender, birth dates, and hire dates, using INSERT statements to populate the table.

*Creating a Table*:
sql
CREATE TABLE Employee (
    staffid varchar (10) NOT NULL,
    FirstName varchar (255) NOT NULL,
    SecondName varchar (255),
    Gender varchar (10),
    Date_of_Birth date,
    HireDate datetime,
    PRIMARY KEY (staffid)
);

![Creating Employee Table](https://github.com/user-attachments/assets/c203a2c4-070e-426b-8e20-89281533a70c)

*Inserting Records into the Table*:
sql
INSERT INTO Employee (staffid, firstname, secondname, gender, Date_of_Birth, hiredate)
VALUES 
    ('AB401', 'ayan', 'olakun', 'female', '1992-08-22', '2018-02-09'),
    ('AB212', 'okorie', 'mercy', 'female', '1988-10-09', '2018-10-09'),
    ('AB223', 'joshua', 'chukwuemeka', 'male', '1980-10-09', '2022-02-09'),
    ('AB234', 'sanni', 'ibrahim', 'male', '1958-10-09', '2019-09-23'),
    ('AB254', 'mercy', 'olanipekun', 'female', '1982-10-09', '2020-02-09'),
    ('AB249', 'johnson', 'mercy', 'female', '1982-10-09', '2019-12-09'),
    ('AB298', 'ayomide', 'halleluyah', 'female', '1982-10-09', '2018-07-11'),
    ('AB260', 'deborah', 'justin', 'female', '1982-10-09', '2018-02-09'),
    ('AB281', 'wale', 'olanipekun', 'male', '1982-10-09', '2018-02-09');

![Inserting Records](https://github.com/user-attachments/assets/df7a4165-5164-4052-bef1-ba4eacca8816)
![Employee Records](https://github.com/user-attachments/assets/16bf9dea-9ae3-48bb-ae44-1e8c5bfb9794)

### 2. Data Manipulation Commands

#### Drop, Delete, and Truncate Commands

- *Drop Table Command*: Removes a table and all its data permanently.
    sql
    DROP TABLE Employee;
    

- *Delete Command*: Removes specific rows from a table based on conditions.
    sql
    DELETE FROM Employee WHERE staffid = 'AB281';
    

- *Truncate Command*: Efficiently removes all rows from a table without deleting the structure.
    sql
    TRUNCATE TABLE Employee;
    

### 3. Identity Property in SQL

The IDENTITY property automatically generates unique numbers for a column, often used for primary keys.

*Creating a Table with Identity*:
sql
CREATE TABLE PERSON (
    personid int IDENTITY (1,1) PRIMARY KEY NOT NULL,
    personname varchar (255) NOT NULL,
    age int
);

INSERT INTO PERSON (personname, age)
VALUES 
    ('saidu', 45),
    ('adebanjo', 49),
    ('olorunda', 33),
    ('martha', 88),
    ('sandi', 100),
    ('jackson', 22),
    ('okunola', 19),
    ('esther', 45);

SELECT * FROM PERSON;

![Creating Identity Table](https://github.com/user-attachments/assets/8e9455bc-0d44-4578-bbdc-36f0daecf209)

### 4. Aggregate Functions in SQL

Aggregate functions perform calculations on a set of values and return a single result, often used with the GROUP BY clause.

*Common Aggregate Functions*:
sql
SELECT SUM(Salary) AS TOTALSALARY FROM Salary;
SELECT AVG(Salary) AS AVERAGESALARY FROM Salary;
SELECT MAX(Salary) AS MAX FROM Salary;
SELECT MIN(Salary) AS MIN FROM Salary;
SELECT COUNT(Staffid) AS EmployeeCount FROM Employee;
SELECT COUNT(Staffid) AS NumberOfEmployee FROM Salary;

1. *SUM*: Calculates the total sum of a numeric column.
   ![SUM Function](https://github.com/user-attachments/assets/cb70ebf9-f9b7-4d09-9ac6-33b24ea4e085)

2. *COUNT*: Returns the number of rows that meet specified criteria.
   ![COUNT Function](https://github.com/user-attachments/assets/1a736307-7349-40a0-ba79-d9c2cde6ac5c)

3. *MAX*: Retrieves the maximum value from a column.
   ![MAX Function](https://github.com/user-attachments/assets/7bed6317-047e-41f1-96d2-fdbc39435a1b)

4. *MIN*: Retrieves the minimum value from a column.
   ![MIN Function](https://github.com/user-attachments/assets/61a0ce16-e2ce-4990-835b-5a8f27365983)

5. *AVG*: Calculates the average value of a numeric column.
   ![AVG Function](https://github.com/user-attachments/assets/1fb5e7f0-e380-458c-9e2b-12c57651d757)

6. *UPDATE*: Modifies existing records in a table.
    sql
    UPDATE Salary
    SET salary = 7056999.9994
    WHERE Staffid = 'AB401';
    

7. *ALTER*: Changes the structure of an existing table.
    sql
    ALTER TABLE Employee
    ADD State_of_Origin varchar (50);

    UPDATE Employee
    SET State_of_Origin = 'Ekiti'
    WHERE staffid = 'AB268';
    

### 5. SQL Clauses

#### 5.1 GROUP BY Clause
The GROUP BY clause groups rows that have the same values in specified columns into summary rows, allowing for aggregate functions to be applied.

sql
SELECT Gender, COUNT(*) AS EmployeeCount
FROM Employee
GROUP BY Gender;


#### 5.2 HAVING Clause
The HAVING clause is used to filter groups based on aggregate conditions, often used in conjunction with GROUP BY.

sql
SELECT Gender, COUNT(*) AS EmployeeCount
FROM Employee
GROUP BY Gender
HAVING COUNT(*) > 2;


#### 5.3 WHERE Clause
The WHERE clause filters records to retrieve only those that meet specific conditions, making data retrieval more efficient.

sql
SELECT * FROM Payment WHERE Payment_Method = 'Cash';


#### 5.4 ORDER BY Clause
The ORDER BY clause is used to sort the result set in either ascending or descending order based on one or more columns.

sql
SELECT * FROM Employee ORDER BY HireDate DESC;


### 6. SQL Operators

#### 6.1 Comparison/Relational Operators
These operators compare values and return a boolean result.
- =: Equal to
- != or <>: Not equal to
- >: Greater than
- <: Less than
- >=: Greater than or equal to
- <=: Less than or equal to

#### 6.2 Range Operators
Used to filter results within a specific range.
- BETWEEN: To filter a set of values within a range.
sql
SELECT * FROM Employee WHERE HireDate BETWEEN '2018-01-01' AND '2018-12-31';


#### 6.3 Logical Operators
These operators combine multiple conditions.
- AND: All conditions must be true.
- OR: At least one condition must be true.
- NOT: Negates a condition.

sql
SELECT * FROM Employee WHERE Gender = 'female' AND HireDate > '2018-01-01';


#### 6.4 UNION and UNION ALL
- UNION: Combines the results of two or more SELECT statements, eliminating duplicates.
- UNION ALL: Combines results without removing duplicates.

sql
SELECT FirstName FROM Employee WHERE Gender = 'male'
UNION
SELECT FirstName FROM Employee WHERE Gender = 'female';


### 7. SQL Views
A view is a virtual table based on the result set of a SQL statement. It can simplify complex queries by providing a straightforward interface.

*Creating a View*:
sql
CREATE VIEW EmployeeView AS
SELECT FirstName, SecondName, HireDate
FROM Employee
WHERE Gender = 'female';


*Querying a View*:
```sql
SELECT * FROM






















