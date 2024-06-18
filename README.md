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

