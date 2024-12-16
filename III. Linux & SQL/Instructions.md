# 1. Application Management in Linux Using APT and Sudo

## Scenario
Your role as a security analyst requires that you have the Suricata and tcpdump network security applications installed on your system.

In this scenario, you have to install, uninstall, and reinstall these applications on your Linux Bash shell. You also need to confirm that you’ve installed them correctly.

Here’s how you'll do this: **First**, you’ll confirm that APT is installed on your Linux Bash shell. **Next**, you’ll use APT to install the Suricata application and confirm that it is installed. **Then**, you’ll uninstall the Suricata application and confirm this as well. **Next**, you’ll install the tcpdump application and list the applications currently installed. **Finally**, you’ll reinstall the Suricata application and confirm that both applications are installed.

### Task 1. Ensure that APT is Installed

### Task 2. Install and Uninstall the Suricata Application

### Task 3. Install the tcpdump application

### Task 4. List the Installed Applications

### Task 5. Reinstall the Suricata Application

# 2. Exploring Linux Shell Interactions: Understanding Input, Output, and Basic Calculations

## Scenario
As a security professional, it’s important to understand the concept of communicating with your computer via the shell.

In this scenario, you have to input a specified string of text that you want the shell to return as output. You'll also need to input a few mathematical calculations so the OS (operating system) can return the result.

Here’s how you’ll do this: **First**, you’ll use the `echo` command to generate some output in the shell. **Second**, you’ll use the `expr` command to perform basic mathematical calculations. **Next**, you’ll use the `clear` command to clear the Bash shell window. **Finally**, you’ll have an opportunity to explore the `echo` and `expr` commands further.




# 3. Linux Commands to Manage File Permissions   

> Please visit this [link](https://www.coursera.org/learn/linux-and-sql?specialization=google-cybersecurity) for further information.

## Scenario 

You are a security professional at a large organization. You mainly work with their research team. Part of your job is to ensure users on this team are authorized with the appropriate permissions. This helps keep the system secure. 

Your task is to examine existing permissions on the file system. You’ll need to determine if the permissions match the authorization that should be given. If they do not match, you’ll need to modify the permissions to authorize the appropriate users and remove any unauthorized access.

**Note:** This scenario involves investigating and updating the same file permissions as the ones in the **Manage authorization lab.**  You can revisit the lab to get screenshots to include in your portfolio document. If you choose, it's also possible to complete this activity without revisiting the lab by typing your commands in the template.

## Check File and Directory Details

In the **Manage authorization** lab, check the permissions set for files and subdirectories in the **projects** directory. Make sure you display all permissions, including hidden files. Or, use the content of Current file permissions document to determine the current permissions. 

Describe the command you can use to check permissions in the **Check file and directory details** section of the **File permissions in Linux** template. From the lab, take a screenshot of the Linux command you used. Or, type this command directly into the template.

Then, use either the output of this command in the lab or the content or the **Current file permissions** document to indicate the current permissions. If using the **Current file permissions** document, write these in the 10-character string that would be part of the command's output.

## Describe the Permissions String

Choose one example from the output in the previous step. In the **Describe the permissions** string section of the **File permissions in Linux** template, write a short description that explains the 10-character string in the example. You should describe what the 10-character string is for and what each character represents.

## Change File Permissions

The organization does not allow others to have write access to any files. Based on the permissions established in Step 3, identify which file needs to have its permissions modified. Use a Linux command to modify these permissions.

Describe the command you used and its output in the **Change file permissions** section of the **File permissions in Linux** template. In the **Manage authorization** lab, take a screenshot of the Linux command you used. Or, type this command directly into the template.

## Change File Permissions on a Hidden File

The research team has archived **.project_x.txt**, which is why it’s a hidden file. This file should not have write permissions for anyone, but the user and group should be able to read the file. Use a Linux command to assign **.project_x.txt** the appropriate authorization.

Describe the command you used and its output in the Change file permissions on a hidden file section of the File permissions in Linux template. In the **Manage authorization** lab, take a screenshot of the Linux command you used. Or, type this command directly into the template.

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

# 4. Using Filters to SQL Queries  

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

## Retrieve employees in Finance or Sales

Your team now needs to perform a different security update on machines for employees in the Sales and Finance departments. Use filters in SQL to create a query that identifies all employees in the Sales or Finance departments. (The department of the employee is found in the **department** column, which contains values that include **Sales** and **Finance**.)

Describe your query and how it works in the Retrieve employees in Finance or Sales section of the Apply filters to SQL queries template. 

In the **Filter with AND, OR, and NOT** lab, take a screenshot of the SQL query you used and copy it into the template. Or, type this query directly into the template.

## Retrieve all employees not in IT

Your team needs to make one more update to employee machines. The employees who are in the Information Technology department already had this update, but employees in all other departments need it. Use filters in SQL to create a query which identifies all employees not in the IT department. (The department of the employee is found in the **department** column, which contains values that include **Information Technology**.)

Describe your query and how it works in the Retrieve all employees not in IT section of the Apply filters to SQL queries template. 

In the **Filter with AND, OR, and NOT** lab, take a screenshot of the SQL query you used and copy it into the template. Or, type this query directly into the template.

## Summary
To finalize the document and make its purpose clear to potential employers, be sure to complete the Project description and Summary sections of the Apply filters to SQL queries template. 

In the Project description section, give a general overview of the scenario and what you accomplish through SQL. Write two to four sentences.

In the Summary section, provide a short summary of the previous tasks and connect them to the scenario. Write approximately two to four sentences.

## What to Include in Your Response

* Be sure to include the following in your completed activity:

* Screenshots of your queries or typed versions of the queries

* Explanations of your queries

* A project description at the beginning

* A summary at the end

* Details on using **LIKE** to search for a pattern

* Details on filtering for dates and times

* Details on using **AND** and **OR** to filter on multiple conditions

* Details on using **NOT** in filters

# 5. Using SQL Joins to Obtain Precise Data   

> Please visit this [link](https://www.coursera.org/learn/linux-and-sql?specialization=google-cybersecurity) for further information.

## Scenario 

You are a security professional at a large organization. You’ll investigate a recent security incident that compromised some machines.

You are responsible for getting the required information from the database for the investigation.

Here’s how you’ll do this task: First, you’ll use an inner join to identify which employees are using which machines. Second, you’ll use left and right joins to find machines that do not belong to any specific user and users who do not have any specific machine assigned to them. Finally, you’ll use an inner join to list all login attempts made by all employees.

## Match Employees to their Machines

First, you must identify which employees are using which machines. The data is located in the **machines** and **employees** tables.

You must use a SQL inner join to return the records you need based on a connecting column. In the scenario, both tables include the **device_id column**, which you’ll use to perform the join.

Complete the query to perform an inner join between the **machines** and **employees** tables on the **device_id column**. 

**Note:** Placing the **employees** table after **INNER JOIN makes** it the right table.

To complete a join you need to link the joined tables on a common column. In the case of the **employees** and **machines** tables, the **device_id** column is common.

## Return More Data

You now must return the information on all machines and the employees who have machines. Next, you must do the reverse and retrieve the information of all employees and any machines that are assigned to them.

To achieve this, you’ll complete a left join and a right join on the **employees** and **machines** tables. The results will include all records from one or the other table. You must link these tables using the common **device_id column**.

**Note:** In a left join, all records from the table referenced after **FROM** and before **LEFT JOIN** are included in the result. In this case, all records from the **machines** table are included, regardless of whether they are assigned to an employee or not.

**Note:** In a right join, all records from the table referenced after **RIGHT JOIN** are included in the result. In this case, all records from the **employees** table are included, regardless of whether they have a machine or not.

## Retrieve Login Attempt Data

To continue investigating the security incident, you must retrieve the information on all employees who have made login attempts. To achieve this, you’ll perform an inner join on the employees and log_in_attempts tables, linking them on the common username column.

**Note:** You must specify the table name with the column name (table.column) when joining the tables.
