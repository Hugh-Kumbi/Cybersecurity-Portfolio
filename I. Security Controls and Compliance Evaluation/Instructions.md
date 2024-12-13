# SQL Queries - Instructions

## Exercise 1: Retrieve Failed Login Attempts
Retrieve all failed login attempts that occurred after working hours (18:00). Ensure the query checks for `success = FALSE` and sorts the results by `login_time`.

Example:
```sql
SELECT * FROM log_in_attempts 
WHERE login_time > '18:00' 
  AND success = FALSE;
