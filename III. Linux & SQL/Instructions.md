# 1. Install Software in a Linux Distribution

## Scenario

Your role as a security analyst requires that you have the Suricata and tcpdump network security applications installed on your system.

In this scenario, you have to install, uninstall, and reinstall these applications on your Linux Bash shell. You also need to confirm that you’ve installed them correctly.

Here’s how you'll do this: **First**, you’ll confirm that APT is installed on your Linux Bash shell. **Next**, you’ll use APT to install the Suricata application and confirm that it is installed. **Then**, you’ll uninstall the Suricata application and confirm this as well. **Next**, you’ll install the tcpdump application and list the applications currently installed. **Finally**, you’ll reinstall the Suricata application and confirm that both applications are installed.

### Task 1. Ensure that APT is Installed

First, you’ll check that the APT application is installed so that you can use it to manage applications. The simplest way to do this is to run the apt command in the Bash shell and check the response.

The Bash shell is the command-line interpreter currently open on the left side of the screen. You’ll use the Bash shell by typing commands after the prompt. The prompt is represented by a dollar sign ($) followed by the input cursor.

* Confirm that the APT package manager is installed in your Linux environment.

### Task 2. Install and Uninstall the Suricata Application

In this task, you must install Suricata, a network analysis tool used for intrusion detection, and verify that it installed correctly. Then, you’ll uninstall the application.

1. Use the APT package manager to install the Suricata application.
2. Verify that Suricata is installed by running the newly installed application.
3. Use the APT package manager to uninstall Suricata.
4. Verify that Suricata has been uninstalled by running the application command again.

### Task 3. Install the tcpdump application

In this task, you must install the tcpdump application. This is a command-line tool that can be used to capture network traffic in a Linux Bash shell.

* Use the APT package manager to install tcpdump.

### Task 4. List the Installed Applications

Next, you need to confirm that you’ve installed the required applications. It's important to be able to validate that the correct applications are installed. Often you may want to check that the correct versions are installed as well.

1. Use the APT package manager to list all installed applications.
2. Search through the list to find the tcpdump application you installed.

### Task 5. Reinstall the Suricata Application

In this task, you must reinstall the Suricata application and verify that it has installed correctly.

1. Run the command to install the Suricata application.
2. Use the APT package manager to list the installed applications.
3. Search through the list to confirm that the Suricata application has been installed.

### Expectations

By completing this activity, you will:

1. Gain hands-on experience using the APT package manager.
2. Learn to:
   * Install applications.
   * Uninstall applications.
   * List installed applications.
3. Develop a key skill for managing installed applications in Linux, essential for any security analyst.

# 2. Examine Input and Output in the Linux Shell

## Scenario

As a security professional, it’s important to understand the concept of communicating with your computer via the shell.

In this scenario, you have to input a specified string of text that you want the shell to return as output. You'll also need to input a few mathematical calculations so the OS (operating system) can return the result.

Here’s how you’ll do this: **First**, you’ll use the `echo` command to generate some output in the shell. **Second**, you’ll use the `expr` command to perform basic mathematical calculations. **Next**, you’ll use the `clear` command to clear the Bash shell window. **Finally**, you’ll have an opportunity to explore the `echo` and `expr` commands further.

### Task 1. Generate output with the echo command

The `echo` command in the Bash shell outputs a specified string of text. In this task, you’ll use the `echo` command to generate output in the Bash shell.

### Task 2. Generate output with the expr command

In this task, you’ll use the `expr` command to generate some additional output in the Bash shell. The `expr` command performs basic mathematical calculations and can be useful when you need to quickly perform a calculation.

Imagine that the system has shown you that you have 32 alerts, but only 8 required action. You want to calculate how many alerts are false positives so that you can provide feedback to the team that configures the alerts.

To do this, you need to subtract the number of alerts that required action from the total number of alerts.

### Task 3. Clear the Bash shell

In this task, you’ll use the `clear` command to clear the Bash shell of all existing output. This allows you to start with the cursor at the top of the Bash shell window.

When you work in a shell environment, the screen can fill with previous input and output data. This can make it difficult to process what you’re working on. Clearing the screen allows you to create a clutter-free text environment to allow you to focus on what is important at that point in time.

### Optional task: Perform more calculations with the expr command

You have the opportunity to explore input and output further using the `echo` and `expr` commands.

1. Generate at least one new output using the `echo` command.
    * (Remember the `echo "hello"` output you generated).

2. Perform at least one new calculation using the `expr` command.

The mathematical operators you can use with the `expr` command for **adding, subtracting, dividing,** and **multiplying** are `+`, `-`, `/` and `*`.

### Expectations

By completing this activity, you will:

1. Gain practical experience in using basic Linux Bash shell commands.
2. Learn to:
    * Generate output with the `echo` command.
    * Generate output with the `expr` command.
    * Clear the Bash shell with the `clear` command.
3. Understand the importance of input and output when communicating through the shell.
4. Build confidence with these basic concepts, preparing you to work with additional commands in the future.

# 3. Find Files with Linux Commands 

## Scenario

In this scenario, you have to locate and analyze the information of certain files located in the /home/analyst directory.

Here’s how you’ll do this: **First**, you’ll get the information of the current working directory you’re in and display the contents of the directory. **Second**, you’ll navigate to the reports directory and list the subdirectories it contains. **Third**, you’ll navigate to the users subdirectory and display the contents of the Q1_added_users.txt file. **Finally**, you’ll navigate to the logs directory and display the first 10 lines of a file it contains.

### Task 1. Get the current directory information

In this task, you must use the commands you learned about to check the current working directory and list its contents.

1. Display your working directory.
2. Display the names of the files and directories in the current working directory.

### Task 2. Change Directory and List the Subdirectories

In this task, you must navigate to a new directory and determine the subdirectories it contains.

1. Navigate to the `/home/analyst/reports` directory.
2. Display the files and subdirectories in the `/home/analyst/reports` directory.

### Task 3. Locate and Read the Contents of a File

In this task, you must navigate to a subdirectory and read the contents of a file it contains.

1. Navigate to the `/home/analyst/reports/users` directory.
2. List the files in the current directory.
3. Display the contents of the `Q1_added_users.txt` file.

### Task 4. Navigate to a directory and locate a file

In this task, you must navigate to a new directory, locate a file, and examine the contents of the file.

1. Navigate to the `/home/analyst/logs` directory.
2. Display the name of the file it contains.
3. Display the first **10** lines of this file.

### Expectations

By completing this activity, you will:

1. Gain practical experience in using basic Linux Bash shell commands.
2. Learn to:
* Navigate directory structures with the cd command.
* Display the current working directory with the pwd command.
* List the contents of a directory with the ls command.
* Display the contents of files with the cat and head commands.
3. Understand that navigating through directories and reading file contents are fundamental skills essential for shell communication.

# 4. Exemplar: Filter with Grep

## Scenario

In this scenario, you need to obtain information contained in server log and user data files. You also need to find files with specific names.

Here’s how you’ll do this: **First**, you’ll navigate to the logs directory and return the error messages in the server_logs.txt file. **Next**, you’ll navigate to the users directory and search for files that contain a specific string in their names. **Finally**, you’ll search for information contained in user files.

With that in mind, you’re ready to practice what you've learned.

### Task 1. Search for Error Messages in a Log File

In this task, you must navigate to the `/home/analyst/logs` directory and report on the error messages in the `server_logs.txt file`. You’ll do this by using `grep` to search the file and output only the entries that are for errors.

### Task 2. Find files containing specific strings

In this task, you must navigate to the `/home/analyst/reports/users` directory and use the correct Linux commands and arguments to search for user data files that contain a specific string in their names.

### Task 3. Search more file contents

In this task, you must search for information contained in user files and report on users that were added and deleted from the system.

### Expectations

By completing this activity, you will:

1. Gain practical experience using grep to:
* Search for specific information contained in files.
* Find files containing specific strings that were piped into grep.
2. Develop the ability to use fundamental Linux tools to filter the information you need.

# 5. Manage Files with Linux Commands  

## Scenario

In this scenario, you need to ensure that the `/home/analys`t directory is properly organized.

You have to make a few changes to the `/home/analyst` directory and the files it contains.

You also have to edit a file to record the changes or updates you make to the directory.

When you start, the `/home/analyst` directory contains the following subdirectories and files:

![image](https://github.com/user-attachments/assets/70dc1c4f-ced5-453f-9ed9-345571ed0cc3)

You need to modify the `/home/analyst` directory to the following directory and file structure:

![image](https://github.com/user-attachments/assets/a4ef22a1-634d-4d34-a226-7c05b08e413c)

Here’s how you’ll do this: **First**, you’ll create a new subdirectory called logs in the `/home/analyst` directory. **Next**, you’ll remove the temp subdirectory. Then, you’ll move the `Q3patches.txt` file to the reports subdirectory and delete the `tempnotes.txt` file. **Finally**, you’ll create a `new .txt` file called tasks in the notes subdirectory and add a note to the file describing the tasks you've performed.

### Task 1. Create a new directory
First, you must create a dedicated subdirectory called `logs`, which will be used to store all future log files.

### Task 2. Remove a Directory
Next, you must remove the temp directory, as you’ll no longer be placing items in it.

### Task 3. Move a File

The `Q3patches.txt` file contains notes taken on third-quarter patches and is now in the correct reporting format.

You must move the  `Q3patches.txt` file from the `notes` directory to the `reports` directory.

### Task 4. Remove a File
Next, you must delete an unused file called `tempnotes.txt` from the `/home/analyst/notes` directory.

### Task 5. Create a new file
Now, you must create a file named `tasks.txt` in the `/home/analyst/notes` directory that you’ll use to document completed tasks.

### Task 6. Edit a file
Finally, you must use the nano text editor to edit the `tasks.txt` file and add a note describing the tasks you’ve completed.

### Expectations
By completing this activity, you will:

1. Gain practical experience using basic Linux Bash shell commands to:
* Create and remove directories.
* Copy, move, and remove files.
* Edit files with the nano text editor.
2. Develop the skills needed to manage directories and files effectively in a Linux environment.

# 6. Linux Commands to Manage File Permissions   

## Manage authorization

### Scenario
In this scenario, you must examine and manage the permissions on the files in the `/home/researcher2/projects` directory for the `researcher2` user.

The `researcher2` user is part of the `research_team` group.

You must check the permissions for all files in the directory, including any hidden files, to make sure that permissions align with the authorization that should be given. When it doesn't, you must change the permissions.

Here’s how you’ll do this task: **First**, you’ll check the user and group permissions for all files in the `projects` directory. **Next**, you’ll check whether any files have incorrect permissions and change the permissions as needed. **Finally**, you’ll check the permissions of the `/home/researcher2/projects/drafts` directory and modify these permissions to remove any unauthorized access.

#### Task 1. Check File and Directory Details
In this task, you must explore the permissions of the `projects` directory and the files it contains. The lab starts with `/home/researcher2` as the current working directory. This is because you're changing permissions for files and directories belonging to the `researcher2` user.

#### Task 2. Change File Permissions
In this task, you must determine whether any files have incorrect permissions and then change the permissions as needed. This action will remove unauthorized access and strengthen security on the system.

None of the files should allow the other users to write to files.

#### Task 3. Change File Permissions on a Hidden File
In this task, you must determine if a hidden file has incorrect permissions and then change the permissions as needed. This action will further remove unauthorized access and strengthen security on the system.

The file `.project_x.txt` is a hidden file that has been archived and should not be written to by anyone. (The user and group should still be able to read this file.)

##### Task 4. Change Directory Permissions
In this task, you must change the permissions of a directory. First, you’ll check the group permissions of the `/home/researcher2/projects/drafts` directory and then modify the permissions as required. (You should be in the `projects` directory while managing the permissions of its subdirectory drafts.)

Only the `researcher2` user should be allowed to access the `drafts` directory and its contents. (This means that only `researcher2` should have execute privileges.)

#### Expectations
By completing this activity, you will:

1. Gain practical experience using basic Linux Bash shell commands to:
* Examine file and directory permissions.
* Change permissions on files.
* Change permissions on directories.
2. Achieve an important milestone in your journey toward managing authorization in Linux.




















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
