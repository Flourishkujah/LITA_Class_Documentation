# LITA_Class_Documentation
This is where I documented my first project while learning data analysis on Incubator Hub

### DATA ANALYSIS WITH EXCEL

## EXCEL FUNCTIONS 

I focused on Excel and worked with a dataset to calculate some key stats. I looked at the grand total and average salaries, pinpointed the highest and lowest salaries, and even found the fourth highest and third lowest salaries. I also played around with conditional functions, which allowed me to dig deeper into the data. I calculated the total salary for Bayelsa, the average salary for Oyo, the highest salary in Edo, the lowest in Taraba, and counted the staff in Nassarawa. Excel’s conditional functions really impressed me with how effectively they can target specific criteria!

![image](https://github.com/user-attachments/assets/87f87278-8ad0-433e-951e-93bbbf01b7d6)

![image](https://github.com/user-attachments/assets/f057e48c-1266-43c2-bc09-af2c9ad01618)


### WORKING WITH VLOOKUP

I explored Excel's VLOOKUP function while working on a salary structure analysis dataset. I used it to retrieve various salary components, such as basic, housing, transport, and leave allowances, all based on the employees' grade levels. This function helped ensure a quick and accurate breakdown of salaries across employees.

My focus was on using VLOOKUP to easily connect employee data with the salary structure, even when handling a large dataset. This allowed for more efficient gross pay calculations while maintaining data consistency across various departments and roles.

![image](https://github.com/user-attachments/assets/8e9d9824-3696-47b1-8ae9-da70f7e7e404)

![image](https://github.com/user-attachments/assets/e31c8fc5-df63-44b0-8f1f-aa69984625df)

![image](https://github.com/user-attachments/assets/1dcf6a3a-0b66-45cc-98be-f42d04e63281)


### Text Extraction Using Excel

I worked with some raw data using text extraction techniques in Excel. By utilizing functions like LEFT(), MID(), and RIGHT(), I was able to break down codes into department codes, purchase dates, and asset category codes. Text extraction is key in transforming raw data into meaningful, structured information for efficient analysis.

![image](https://github.com/user-attachments/assets/ead819cd-2964-440e-b87e-c837391cf11a)

![image](https://github.com/user-attachments/assets/a768c62a-e783-4c48-8518-6d463b4015b6)


### Data cleaning with Excel

I focused on data cleaning, and it truly makes a big difference when working with properly cleaned data. I combined first and last names to create full names, then used the first names to generate emails using Excel’s “ & “ function. These small steps make data more readable and manageable.

Data cleaning is one of the most important steps in data analysis. Just like an engineer gathering tools and clearing the workspace, data cleaning lays the foundation for reliable insights.

![image](https://github.com/user-attachments/assets/bd7edd13-2881-48a8-a69c-1b3e7b2a86ef)
![image](https://github.com/user-attachments/assets/96b66b81-8692-4efc-b52e-84e04df05247)
![image](https://github.com/user-attachments/assets/096ce4eb-4254-4d7f-a0f5-99958bd676f4)
![image](https://github.com/user-attachments/assets/59af3c3d-f6f7-4baf-93b1-2aa92bc4fa6e)


### Mastering Text Cleaning with Excel

The focus was on text cleaning and formatting in Excel. I worked through issues like inconsistent formatting, extra spaces, and pulling key details from strings. Using a mix of Excel functions, I turned messy raw data into something much cleaner and easier to work with, without losing any important details.
I used PROPER, UPPER, and LOWER functions to make sure names had consistent capitalization. The TRIM function came in handy to get rid of those annoying extra spaces, making everything more readable. I also used LEFT to pull specific info like first names or surnames, which made the data easier to manage.
Having clean data makes everything so much smoother and even more accurate.

![image](https://github.com/user-attachments/assets/31b6c8a0-8f67-4a2d-8fdb-dcde5bf33f39)
![image](https://github.com/user-attachments/assets/e4fafc08-d67d-4bec-82bb-e5135af39b0d)
![image](https://github.com/user-attachments/assets/a01362c3-ab5f-4b7f-b21d-1bcaf6e32c44)
![image](https://github.com/user-attachments/assets/d498149a-1fc0-4c59-82d7-519dfa1d7999)


### Unlocking Insights with Pivot Tables

I spent time using pivot tables in Excel to explore sales across different regions and stores. Pivot tables make it easy to arrange and summarize large amounts of data, so I could quickly see which areas were doing well:

1. Top Region: North East earned ₦18.6 billion.

2. Best Store: Ankpa had the highest sales with ₦1.7 billion.

This tool helps me break down data and find patterns that might be missed. It’s a simple way to understand what’s working and what needs attention. 

![image](https://github.com/user-attachments/assets/fb285a50-39c6-477d-bb49-6c7adb708af2)
![image](https://github.com/user-attachments/assets/374aaa9d-4650-4f02-8434-673c37d39be0)

### Unlocking Insights with Pivot Tables

I worked with pivot tables in Excel to analyze the sales and revenue data, and the insights were eye-opening!

Top Markets by Revenue: Ekiti came out on top with ₦5.57 billion, with Abia and Bayelsa not far behind. Together, the top 10 markets generated over ₦22 billion—pretty impressive!

Bottom 5 Stores by Units Sold: Some stores like Boki and Kwali had lower sales, which could mean room for growth or areas to re-evaluate.

Regional Revenue Averages: It’s interesting to see that the South South region has the highest average revenue, while North Central comes in lower at around ₦3.5 million. These patterns might reveal something about customer demand in each region.

Line of Business Breakdown: Service Plans really lead in revenue, with Copier and Printer Sales close behind. Knowing which areas drive revenue can help pinpoint where to focus future efforts.



![image](https://github.com/user-attachments/assets/875b3415-1ead-4955-8abb-33cf3ea8f272)
![image](https://github.com/user-attachments/assets/0cc4692d-2f81-4ed6-bba8-2fc12556f373)


## DATA ANALYSIS WITH SQL

### Building Foundations with SQL Tables and Queries

Today, I worked on creating and managing tables in SQL Server. I created an Employee table with details like names, gender, birth dates, and hire dates, and practiced inserting records. Each query I run teaches me something new!

The "staffid" serves as the primary key, ensuring each employee record is unique—a fundamental yet crucial aspect of database design! Adding records for different employees was a good exercise in understanding data structures and maintaining consistency.

I used SELECT statements to retrieve specific columns like staff IDs and first names. These queries show how to access and organize data with precision. This hands-on experience with tables and primary keys is a reminder of how SQL is essential for real-world data management and analysis.

TO CREATE A TABLE 

```
CREATE TABLE Employee (
staffid varchar (10) not null,
FirstName varchar (255) NOT NULL,
SecondName varchar (255),
Gender varchar (10),
Date_of_Birth date,
HireDate datetime,
primary key (staffid)
)
```

![image](https://github.com/user-attachments/assets/c203a2c4-070e-426b-8e20-89281533a70c)


TO INSERT INTO THE TABLE 
```
select staffid, firstname from Employee

insert into Employee (staffid, firstname, secondname, gender,Date_of_Birth,
hiredate)
values ( 'AB401', 'ayan', 'olakun', 'female', '1992-08-22', '2018-02-09'),
( 'AB212', 'okorie', 'mercy', 'female','1988-10-09', '2018-10-09'),
( 'AB223', 'joshua', 'chukwuemeka', 'male','1980-10-09', '2022-02-09'),
( 'AB234', 'sanni', 'ibrahim', 'male','1958-10-09', '2019-09-23'),
( 'AB254', 'mercy', 'olanipekun', 'female','1982-10-09', '2020-02-09'),
( 'AB249', 'johnson', 'mercy', 'female','1982-10-09', '2019-12-09'),
( 'AB298', 'ayomide', 'halleluyah', 'female', '1982-10-09','2018-07-11'),
( 'AB260', 'deborah', 'justin', 'female','1982-10-09', '2018-02-09'),
( 'AB281', 'wale', 'olanipekun', 'male','1982-10-09', '2018-02-09')
```

![image](https://github.com/user-attachments/assets/df7a4165-5164-4052-bef1-ba4eacca8816)
![image](https://github.com/user-attachments/assets/16bf9dea-9ae3-48bb-ae44-1e8c5bfb9794)

### DROP, DELETE AND TRUNCATE COMMAND IN SQL

### 1. Drop Table Command
This command is used to completely remove a table from the database, including all of its data and structure. Once a table is dropped, all data and any dependent database objects, like constraints, indexes, and triggers, are permanently deleted, and the action cannot be undone.
```
DROP TABLE employee
```

### 2. Delete Command
The DELETE command is used to remove specific rows from a table based on a condition. In this case, it deletes the row(s) from the employee table where the staffid equals 'ab281'. The table structure and other data remain unchanged. If no condition is specified, all rows in the table will be deleted, but the table itself will remain.

```
DELETE FROM employee WHERE staffid = 'ab281'
```

### 3. Truncate Command
The TRUNCATE command removes all rows from a table, quickly and efficiently. Unlike DELETE, TRUNCATE does not generate individual row delete operations and does not allow for conditional deletion. The table structure remains in the database for future use. This command cannot be rolled back in some database systems, as it is often considered a more permanent data removal method than DELETE.

```
TRUNCATE TABLE employee
```

### Identity in SQL
The IDENTITY property in SQL is used to generate unique numbers automatically for a column, typically used for primary keys. The IDENTITY property specifies that the column will have an auto-incrementing value starting from a given seed and incremented by a specified step.

```
CREATE TABLE PERSON (
personid int identity (1,1) primary key not null,
personname varchar (255) not null,
age int
)
insert into PERSON (personname, age)
values ('saidu', 45),
('adebanjo', 49),
('olorunda', 33),
('martha', 88),
('sandi', 100),
('jackson', 22),
('okunola', 19),
('esther', 45)
select * from PERSON
```

![image](https://github.com/user-attachments/assets/8e9455bc-0d44-4578-bbdc-36f0daecf209)


## Aggregate Functions in SQL
Aggregate functions perform calculations on a set of values and return a single value. They are commonly used in conjunction with the GROUP BY clause to summarize data. Here are descriptions of the specific functions mentioned:

## Functions

```
SELECT SUM(Salary) AS TOTALSALARY FROM Salary
SELECT AVG(Salary) AS AVERAGESALARY FROM Salary
SELECT MAX(Salary) AS MAX FROM Salary
SELECT MIN(Salary) AS MIN FROM Salary
SELECT COUNT(Staffid) AS EmployeeCount FROM EMPLOYEE
SELECT COUNT(Staffid) AS NumberOfEmployee FROM Salary
```

1. **SUM**: Calculates the total sum of a numeric column.

![image](https://github.com/user-attachments/assets/cb70ebf9-f9b7-4d09-9ac6-33b24ea4e085)

2. **COUNT**: Returns the number of rows that match a specified condition or the total number of rows in a table.

![image](https://github.com/user-attachments/assets/1a736307-7349-40a0-ba79-d9c2cde6ac5c)

3. **MAX**: Retrieves the maximum value from a specified column.

![image](https://github.com/user-attachments/assets/7bed6317-047e-41f1-96d2-fdbc39435a1b)

4. **MIN**: Retrieves the minimum value from a specified column.

![image](https://github.com/user-attachments/assets/61a0ce16-e2ce-4990-835b-5a8f27365983)

5. **AVG (Average)**: Calculates the average value of a numeric column.

![image](https://github.com/user-attachments/assets/1fb5e7f0-e380-458c-9e2b-12c57651d757)

6. **UPDATE**: The UPDATE command is used to modify existing records in a table. The SET clause specifies the column to be updated and the new value, while the WHERE clause ensures that only the specific record matching the condition is affected. Without the WHERE clause, all rows in the table would be updated, which can be risky.

```
UPDATE Salary
SET salary = 7056999.9994
WHERE Staffid = 'AB401';
```

7. **ALTER**: The ALTER command is used to modify the structure of an existing table in a database. It allows for changes such as adding new columns, deleting existing columns, or modifying the data type of columns. The ALTER command is powerful and helps manage database tables without affecting the existing data in those tables.

```
ALTER TABLE EMPLOYEE
ADD State_of_Origin varchar (50)
select * from employee
UPDATE EMPLOYEE
SET State_of_Origin = 'Ekiti'
where staffid = 'AB268'
```














