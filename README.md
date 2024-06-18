![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-4/assets/170050432/bdd1b997-3a77-414b-b54e-79d24f3d7d04)

# Basic-SQL-Queries-Operators-Filters-Lab-4

# Task 1. Retrieve after hours failed login attempts

I need to investigate failed login attempts that were made after business hours. To retrieve this information from the login activity, I will identify all unsuccessful attempts after 18:00. 
The `login_time` column in the `log_in_attempts` table contains information on when login attempts were made, and office hours end at '18:00'. 
The `success` column in the `log_in_attempts` table contains values of TRUE or FALSE to indicate whether the login was successful. MySQL stores Boolean values as 1 for TRUE and 0 for FALSE. 
This means that TRUE is represented as 1, and FALSE is represented as 0 in the `success` column. 
I will use the AND operator to retrieve the failed login attempts that occurred after business hours. I will replace the X and Y with the correct values to filter for the records I need.

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-4/assets/170050432/3089dcba-0424-45d4-99be-35d38474a209)
![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-4/assets/170050432/6b7c8dea-5897-4bd4-9578-b0fdf084304c)


# Task 2. Retrieve login attempts on specific dates

I need to investigate a suspicious event that occurred on '2022-05-09'. 
To retrieve all login attempts that occurred on this day and the day before ('2022-05-08'), I will use the OR operator to filter the records. 
The `login_date` column in the `log_in_attempts` table contains information on the dates when login attempts were made. 
I will replace the X and Y with the correct values to filter for the records I need:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-4/assets/170050432/298b3902-f2bf-4105-a571-2e5fc5e1728f)



# Task 3. Retrieve login attempts outside of Mexico

I need to investigate logins that did not originate in Mexico. 
The `country` field includes entries with 'MEX' and 'MEXICO'. To find this information, I will use the NOT and LIKE operators with the matching pattern 'MEX%'. 
I will replace X with the correct operator and Y with the correct pattern to filter for the information I need:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-4/assets/170050432/de7bd844-b931-41de-9aba-36894af1d7b5)


# Task 4. Retrieve employees in Marketing

For tasks 4, 5, and 6, I need to retrieve the information from the `department` and `office` columns in the `employees` table. I can run the following SQL query if I need to view the columns and values in the `employees` table:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-4/assets/170050432/ff736fb1-bece-4e98-bdff-bc80733df2ba)

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-4/assets/170050432/329d0ccb-e63d-4f54-90be-3547aed6a991)


# Task 5. Retrieve employees in Finance or Sales

To locate information on employees in the Finance or Sales department for an update to their computers, I will write a SQL query to retrieve records for employees in these departments:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-4/assets/170050432/c7402ed1-b818-4778-907b-74e6f078e289)


# Task 6. Retrieve all employees not in IT

To retrieve records for employees who are not in the 'Information Technology' department, I will use the NOT operator to identify these employees:

![image](https://github.com/iahalkhatib/Basic-SQL-Queries-Operators-Filters-Lab-4/assets/170050432/4a6ac9d0-373c-4779-9bc3-d1912d4fd1ab)


# I now have practical experience in using SQL to:

- Run SQL queries to retrieve information from a database.
- Apply AND, OR, and NOT operators to filter SQL queries.
