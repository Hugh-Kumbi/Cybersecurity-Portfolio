# Linux Commands to Manage File Permissions   

> Please visit this [link](https://www.coursera.org/learn/linux-and-sql?specialization=google-cybersecurity) for further information.

## Scenario 

You are a security professional at a large organization. Part of your job is to investigate security issues to help keep the system secure. You recently discovered some potential security issues that involve login attempts and employee machines.

Your task is to examine the organization’s data in their **employees** and **log_in_attempts** tables. You’ll need to use SQL filters to retrieve records from different datasets and investigate the potential security issues.

**Note:** This scenario involves the same queries as the ones the **Filter with AND, OR, and NOT** lab. You can revisit the lab to get screenshots to include in your portfolio document. If you choose, it's also possible to complete this activity without revisiting the lab by typing your queries in the template

## Retrieve After Hours Failed login Attempts

You recently discovered a potential security incident that occurred after business hours. To investigate this, you need to query the **log_in_attempts** table and review after hours login activity. Use filters in SQL to create a query that identifies all failed login attempts that occurred after 18:00. (The time of the login attempt is found in the **login_time** column. The success column contains a value of 0 when a login attempt failed; you can use either a value of **0** or **FALSE** in your query to identify failed login attempts.)

Describe your query and how it works in the Retrieve after hours failed login attempts section of the Apply filters to SQL queries template. 

In the **Filter with AND, OR, and NOT** lab, take a screenshot of the SQL query you used and copy it into the template. Or, type this query directly into the template.

## Retrieve Login Attempts on Specific Dates

A suspicious event occurred on 2022-05-09. To investigate this event, you want to review all login attempts which occurred on this day and the day before. Use filters in SQL to create a query that identifies all login attempts that occurred on 2022-05-09 or 2022-05-08. (The date of the login attempt is found in the **login_date** column.)

Describe your query and how it works in the Retrieve login attempts on specific dates section of the Apply filters to SQL queries template. 

In the **Filter with AND, OR, and NOT** lab, take a screenshot of the SQL query you used and copy it into the template. Or, type this query directly into the template.

## Retrieve Login Attempts outside of Mexico

There’s been suspicious activity with login attempts, but the team has determined that this activity didn't originate in Mexico. Now, you need to investigate login attempts that occurred outside of Mexico. Use filters in SQL to create a query that identifies all login attempts that occurred outside of Mexico. (When referring to Mexico, the **country** column contains values of both **MEX** and **MEXICO**, and you need to use the **LIKE** keyword with % to make sure your query reflects this.)

Describe your query and how it works in the Retrieve login attempts on specific dates section of the Apply filters to SQL queries template. 

In the **Filter with AND, OR, and NOT** lab, take a screenshot of the SQL query you used and copy it into the template. Or, type this query directly into the template.

## Retrieve employees in Marketing

Your team wants to perform security updates on specific employee machines in the Marketing department. You’re responsible for getting information on these employee machines and will need to query the **employees** table. Use filters in SQL to create a query that identifies all employees in the Marketing department for all offices in the East building.

(The department of the employee is found in the **department** column, which contains values that include **Marketing**. The office is found in the office column. Some examples of values in this column are **East-170**, **East-320**, and **North-434**. You’ll need to use the LIKE keyword with % to filter for the East building.)

Describe your query and how it works in the Retrieve employees in Marketing section of the Apply filters to SQL queries template. 

In the **Filter with AND, OR, and NOT** lab, take a screenshot of the SQL query you used and copy it into the template. Or, type this query directly into the template.

## Change directory permissions

The files and directories in the projects directory belong to the **researcher2** user. Only **researcher2** should be allowed to access the drafts directory and its contents. Use a Linux command to modify the permissions accordingly.

Describe the command you used and its output in the **Change directory permissions** section of the **File permissions in Linux** template. In the **Manage authorization** lab, take a screenshot of the Linux command you used. Or, type this command directly into the template.

## Summary

To finalize the document and make its purpose clear to potential employers, be sure to complete the **Project description** and **Summary** sections of the **File permissions in Linux** template. 

In the Project description section, give a general overview of the scenario and what you accomplish through Linux. Write two to four sentences.

In the Summary section, provide a short summary of the previous tasks and connect them to the scenario. Write approximately two to four sentences.

## What to Include in Your Response
* Be sure to include the following in your completed activity:

* Screenshots of your commands or typed versions of the commands

* Explanations of your commands

* A project description at the beginning

* A summary at the end

* Details on using chmod to update file permissions

* Details on checking file permissions with ls -la

* Details on interpreting the 10-character string that represents file permissions

* Details on hidden files and directories
