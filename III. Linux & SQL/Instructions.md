# 1. Install Software in a Linux Distribution

> Please visit this [link](https://www.coursera.org/learn/linux-and-sql?specialization=google-cybersecurity) for further information.

## Scenario

Your role as a security analyst requires that you have the Suricata and tcpdump network security applications installed on your system.

In this scenario, you have to install, uninstall, and reinstall these applications on your Linux Bash shell. You also need to confirm that you’ve installed them correctly.

Here’s how you'll do this: **First**, you’ll confirm that APT is installed on your Linux Bash shell. **Next**, you’ll use APT to install the Suricata application and confirm that it is installed. **Then**, you’ll uninstall the Suricata application and confirm this as well. **Next**, you’ll install the tcpdump application and list the applications currently installed. **Finally**, you’ll reinstall the Suricata application and confirm that both applications are installed.

### Task 1. Ensure that APT is Installed

First, you’ll check that the APT application is installed so that you can use it to manage applications. The simplest way to do this is to run the apt command in the Bash shell and check the response.

The Bash shell is the command-line interpreter currently open on the left side of the screen. You’ll use the Bash shell by typing commands after the prompt. The prompt is represented by a dollar sign ($) followed by the input cursor.

### Task 2. Install and Uninstall the Suricata Application

In this task, you must install Suricata, a network analysis tool used for intrusion detection, and verify that it installed correctly. Then, you’ll uninstall the application.

### Task 3. Install the Tcpdump Application

In this task, you must install the tcpdump application. This is a command-line tool that can be used to capture network traffic in a Linux Bash shell.

### Task 4. List the Installed Applications

Next, you need to confirm that you’ve installed the required applications. It's important to be able to validate that the correct applications are installed. Often you may want to check that the correct versions are installed as well.

### Task 5. Reinstall the Suricata Application

In this task, you must reinstall the Suricata application and verify that it has installed correctly.

### Expectations

By completing this activity, you will:

1. Gain hands-on experience using the APT package manager.
2. Learn to:
   * Install applications.
   * Uninstall applications.
   * List installed applications.
3. Develop a key skill for managing installed applications in Linux, essential for any security analyst.

# 2. Examine Input and Output in the Linux Shell

> Please visit this [link](https://www.coursera.org/learn/linux-and-sql?specialization=google-cybersecurity) for further information.

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

> Please visit this [link](https://www.coursera.org/learn/linux-and-sql?specialization=google-cybersecurity) for further information.

## Scenario

In this scenario, you have to locate and analyze the information of certain files located in the /home/analyst directory.

Here’s how you’ll do this: **First**, you’ll get the information of the current working directory you’re in and display the contents of the directory. **Second**, you’ll navigate to the `reports` directory and list the subdirectories it contains. **Third**, you’ll navigate to the `users` subdirectory and display the contents of the `Q1_added_users.txt file`. **Finally**, you’ll navigate to the `logs` directory and display the first 10 lines of a file it contains.

### Task 1. Get the current directory information

In this task, you must use the commands you learned about to check the current working directory and list its contents.

### Task 2. Change Directory and List the Subdirectories

In this task, you must navigate to a new directory and determine the subdirectories it contains.

### Task 3. Locate and Read the Contents of a File

In this task, you must navigate to a subdirectory and read the contents of a file it contains.

### Task 4. Navigate to a directory and locate a file

In this task, you must navigate to a new directory, locate a file, and examine the contents of the file.

### Expectations

By completing this activity, you will:

1. Gain practical experience in using basic Linux Bash shell commands.
2. Learn to:
* Navigate directory structures with the `cd` command.
* Display the current working directory with the `pwd` command.
* List the contents of a directory with the `ls` command.
* Display the contents of files with the `cat` and `head` commands.
3. Understand that navigating through directories and reading file contents are fundamental skills essential for shell communication.

# 4. Filter with Grep

> Please visit this [link](https://www.coursera.org/learn/linux-and-sql?specialization=google-cybersecurity) for further information.

## Scenario

In this scenario, you need to obtain information contained in server log and user data files. You also need to find files with specific names.

Here’s how you’ll do this: **First**, you’ll navigate to the `logs` directory and return the error messages in the `server_logs.txt` file. **Next**, you’ll navigate to the `users` directory and search for files that contain a specific string in their names. **Finally**, you’ll search for information contained in user files.

### Task 1. Search for Error Messages in a Log File

In this task, you must navigate to the `/home/analyst/logs` directory and report on the error messages in the `server_logs.txt file`. You’ll do this by using `grep` to search the file and output only the entries that are for errors.

### Task 2. Find Files Containing Specific Strings

In this task, you must navigate to the `/home/analyst/reports/users` directory and use the correct Linux commands and arguments to search for user data files that contain a specific string in their names.

### Task 3. Search More File Contents

In this task, you must search for information contained in user files and report on users that were added and deleted from the system.

### Expectations

By completing this activity, you will:

1. Gain practical experience using `grep` to:
* Search for specific information contained in files.
* Find files containing specific strings that were piped into `grep`.
2. Develop the ability to use fundamental Linux tools to filter the information you need.

# 5. Manage Files with Linux Commands  

> Please visit this [link](https://www.coursera.org/learn/linux-and-sql?specialization=google-cybersecurity) for further information.

## Scenario

In this scenario, you need to ensure that the `/home/analys`t directory is properly organized.

You have to make a few changes to the `/home/analyst` directory and the files it contains.

You also have to edit a file to record the changes or updates you make to the directory.

When you start, the `/home/analyst` directory contains the following subdirectories and files:

![image](https://github.com/user-attachments/assets/70dc1c4f-ced5-453f-9ed9-345571ed0cc3)

You need to modify the `/home/analyst` directory to the following directory and file structure:

![image](https://github.com/user-attachments/assets/a4ef22a1-634d-4d34-a226-7c05b08e413c)

Here’s how you’ll do this: **First**, you’ll create a new subdirectory called logs in the `/home/analyst` directory. **Next**, you’ll remove the `temp` subdirectory. **Then**, you’ll move the `Q3patches.txt` file to the `reports` subdirectory and delete the `tempnotes.txt` file. **Finally**, you’ll create a new `.txt` file called `tasks` in the `notes` subdirectory and add a note to the file describing the tasks you've performed.

### Task 1. Create a New directory
First, you must create a dedicated subdirectory called `logs`, which will be used to store all future log files.

### Task 2. Remove a Directory
Next, you must remove the `temp` directory, as you’ll no longer be placing items in it.

### Task 3. Move a File

The `Q3patches.txt` file contains notes taken on third-quarter patches and is now in the correct reporting format.

You must move the  `Q3patches.txt` file from the `notes` directory to the `reports` directory.

### Task 4. Remove a File
Next, you must delete an unused file called `tempnotes.txt` from the `/home/analyst/notes` directory.

### Task 5. Create a New File
Now, you must create a file named `tasks.txt` in the `/home/analyst/notes` directory that you’ll use to document completed tasks.

### Task 6. Edit a File
Finally, you must use the nano text editor to edit the `tasks.txt` file and add a note describing the tasks you’ve completed.

### Expectations
By completing this activity, you will:

1. Gain practical experience using basic Linux Bash shell commands to:
* Create and remove directories.
* Copy, move, and remove files.
* Edit files with the nano text editor.
2. Develop the skills needed to manage directories and files effectively in a Linux environment.

# 6. Linux Commands to Manage File Permissions   

> Please visit this [link](https://www.coursera.org/learn/linux-and-sql?specialization=google-cybersecurity) for further information.

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

# 7. Use Linux Commands to Manage File Permissions

> Please visit this [link](https://www.coursera.org/learn/linux-and-sql?specialization=google-cybersecurity) for further information.

## Scenario 

You are a security professional at a large organization. You mainly work with their research team. Part of your job is to ensure users on this team are authorized with the appropriate permissions. This helps keep the system secure. 

Your task is to examine existing permissions on the file system. You’ll need to determine if the permissions match the authorization that should be given. If they do not match, you’ll need to modify the permissions to authorize the appropriate users and remove any unauthorized access.

**Note:** This scenario involves investigating and updating the same file permissions as the ones in the **Manage authorization lab.**  You can revisit the lab to get screenshots to include in your portfolio document. If you choose, it's also possible to complete this activity without revisiting the lab by typing your commands in the template.

## Access Supporting Materials
The following supporting materials will help you complete this activity. Keep them open as you proceed to the next steps. 

To use the supporting materials for this course item, click the following links.

The **Instructions for including Linux commands** document provides instructions and best practices for including samples of Linux commands in your portfolio activity.

  * Link to supporting material: [Instructions for including Linux commands](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/Instructions%20for%20Including%20Linux%20Commands.pdf)

The **Current file permissions** document demonstrates how the file structure is built for this portfolio activity. The file permissions for each file or directory are also provided.

  * Link to supporting material: [Current file permissions](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/Current%20file%20Permissions.pdf)

**Note:** It is recommended that you use the **Manage authorization** lab to complete this portfolio activity. If you’re revisiting the lab, using the **Current file permissions** document is optional because this file structure has already been created for you.

## Check File and Directory Details

In the **Manage authorization** lab, check the permissions set for files and subdirectories in the **projects** directory. Make sure you display all permissions, including hidden files. Or, use the content of [Current file permissions](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/Current%20file%20Permissions.pdf) document to determine the current permissions. 

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

## Change Directory Permissions

The files and directories in the projects directory belong to the **researcher2** user. Only **researcher2** should be allowed to access the **drafts** directory and its contents. Use a Linux command to modify the permissions accordingly.

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

* Details on using **chmod** to update file permissions

* Details on checking file permissions with **ls -la**

* Details on interpreting the 10-character string that represents file permissions

* Details on hidden files and directories

# 8. Add and Manage Users with Linux Commands

> Please visit this [link](https://www.coursera.org/learn/linux-and-sql?specialization=google-cybersecurity) for further information.

## Scenario 

In this scenario, a new employee with the username researcher9 joins an organization. You have to add them to the system and continue to manage their access during their time with the organization.

Here’s how you’ll do this task: **First**, you’ll add a new employee to the system and then to their primary group. **Second**, you’ll make this employee the owner of a file related to a particular project. **Third**, you’ll add the new employee to a supplementary group. **Finally**, you’ll delete the employee from the system.

### Task 1. Add a New User

A new employee has joined the Research department. In this task, you must add them to the system. The username assigned to them is `researcher9`.

### Task 2. Assign File Ownership
The new employee, `researcher9`, will take responsibility for `project_r`. In this task, you must make them the owner of the `project_r.txt` file.

The `project_r.txt` file is located in the `/home/researcher2/projects` directory, and owned by the `researcher2` user.

### Task 3. Add the User to a Secondary Group
A couple of months later, this employee's role at the organization has changed, and they are working in both the Research and the Sales departments.

In this task, you must add `researcher9` to a secondary group (`sales_team`). Their primary group is still `research_team`.

### Task 4. Delete a User
A year later, `researcher9`, decided to leave the company. In this task, you must remove them from the system.

### Expectations
By completing this activity, you will:

1. Gain practical experience using basic Linux Bash shell commands to:
* Add a new user.
* Add a user to a group.
* Change user permissions on files.
* Delete a user.
2. Achieve an important milestone in your journey toward managing users in Linux.

# 9. Get Help in the Command Line

> Please visit this [link](https://www.coursera.org/learn/linux-and-sql?specialization=google-cybersecurity) for further information.

## Scenario 

In this scenario, you have to find more information about commands that you need to use. You also need to discover which command to use to perform a certain task.

Here’s how you’ll do this task: `First`, you’ll explore a few commands you can use in the shell to learn more about other commands. `Next`, you’ll find an option you need to add to a command. `Third`, you’ll use a command to get a brief description of commands so you can identify their differences. `Finally`, you’ll identify the command you need to perform a task.

### Task 1. Learn More About Commands

In this task, you need to explore a few commands you can use in the shell to learn more about the functionality of other commands.

`First`, imagine you can’t quite remember what the `cat` command does and want a quick reminder.

### Task 2. Explore the Useradd Command

In this task, imagine that you want to set the expiration date for a temporary user account. You know that you need to use the `useradd` command for this, but you’re not quite sure how to complete the task. You realize it might involve adding an option to the command.

### Task 3. Explore the Rm and Rmdir Commands

In this task, you need to determine the difference between the `rm` and `rmdir` commands.

Imagine that you’ve used these commands before, but you can’t remember how they’re different.

### Task 4. Determine Which Command to Use

In this task, imagine that you need to create a new group but you can’t remember what command to use. You need to identify a command that will do this by searching for it through keywords. In this case, use the keywords `create new group`.

### Expectations
By completing this activity, you will:

1. Gain practical experience using basic Linux Bash shell commands to:
 * Get a short description of a command.
 * Display the man pages for a command.
 * Find commands based on keywords about their function.
2. Develop a valuable skill set for effectively navigating the Linux command line.

# 10. Perform an SQL Query

> Please visit this [link](https://www.coursera.org/learn/linux-and-sql?specialization=google-cybersecurity) for further information.

## Scenario 

In this scenario, you have to determine which employee devices must be updated. You also need to investigate user login activity to explore if any unusual activity has occurred.

The information you need is located in the `machines` and `login_attempts` tables in the `organization` database.

Here’s how you’ll do this task: **First**, you’ll obtain information on the employee devices that must be updated. **Next**, you’ll examine the login attempts for unusual activity. **Finally**, you’ll use the `ORDER BY` keyword to sort the data returned by your SQL queries.

### Task 1. Retrieve Employee Device Data

In this task, you need to obtain information on employee devices because your team needs to update them. The information you need is in the `machines` table in the `organization` database.

**First**, you need to retrieve all the information about the employee devices.
**Next**, you want to focus on the email client running on various devices.
**Finally**, you need information on the operating systems used on various devices and their last patch date.

### Task 2. Investigate Login Activity

In this task, you need to analyze the information from the log_in_attempts table to determine if any unusual activity has occurred.

**First**, you need to investigate the locations where login attempts were made to ensure that they’re in expected areas (the United States, Canada, or Mexico).
**Next**, you need to check if login attempts were made outside of the organization's working hours.
**Finally**, you need to get a complete picture of all login attempts.

### Task 3. Order Login Attempts Data

In this task, you need to use the `ORDER` BY keyword. You'll sequence the data that your query returns according to the login date and time.

**First**, you need to sort the information by date.
**Next**, you need to further organize the previous results by ordering them by `login_time`.

### Expectations

By completing this activity, you will:

1. Gain practical experience in running basic SQL queries to:
* Select specific columns from a table.
* Select all columns from a table using an asterisk (`*`).
* Sort query results using the `ORDER BY` keyword.
2. Build a strong foundation for running more advanced queries and applying filters in the future.

# 11. Filter a SQL query  

> Please visit this [link](https://www.coursera.org/learn/linux-and-sql?specialization=google-cybersecurity) for further information.

## Scenario

In this scenario, you need to get specific information about employees, their machines, and the departments they’re in. Your team needs this data to perform various tasks, such as running updates, posting a privacy notice in certain departments, and sending an alert to an employee with an issue on a machine.

You are responsible for finding the required information by querying a database. You’ll add filters to your queries to locate the information more quickly.

Here’s how you’ll do this task: **First**, you’ll list all organization machines and their operating systems. **Second**, you’ll list all machines with the operating system OS 2. **Third**, you’ll list all the employees in the Finance and Sales departments. **Fourth**, you’ll obtain information about machines.

### Task 1. List All Organization Machines

In this task, you need to get a list of all organization machines and their operating systems. The data is contained in the `machines` table. You’ll need to use the `SELECT` keyword to return specific columns.

### Task 2. Retrieve a List of the machines with OS 2

In this task, you need to obtain a list of all machines with the `'OS 2'` operating system because these machines need an update. To get this information, you’ll run your first SQL query with a filter.

### Task 3. List Employees in Specific Departments

In this task, you need to retrieve a list of all the employees in the Finance and Sales departments to obtain their office numbers. A notice about handling confidential financial information will be posted to these offices.

### Task 4. Identify Employee Machines

Your team recently discovered that there are issues with machines in the South building. In this task, you need to obtain certain employee and computer information.

A machine in `'South-109'` has an issue. You need to determine which employee uses that computer so you can send them an alert.

Next, your team has determined that there is an issue with all the machines in the South building. Offices in the organization are named with the building name, a hyphen, and the office number in that building (for example, `'South-109'`).

### Expectations
By completing this activity, you will:

1. Gain practical experience in using SQL to:
* Apply the `WHERE` clause to filter query results.
* Use the `LIKE` operator to filter for patterns.
2. Take an important step toward running SQL queries to extract specific data from a database.

# 12. Apply More Filters in SQL

> Please visit this [link](https://www.coursera.org/learn/linux-and-sql?specialization=google-cybersecurity) for further information.

## Scenario

In this scenario, you’re investigating a recent security incident.

You need to gather information about login attempts for certain dates and times. This will help in resolving a security incident.

Here’s how you’ll do this task: **First**, you’ll retrieve login events made after a certain date. **Second**, you’ll narrow the focus of the search to filter logins in a date range. **Third**, you’ll investigate logins that were made at certain times. **Finally**, you’ll filter login attempts based on their event IDs.

### Task 1. Retrieve Login Attempts After a Certain Date
In this task, you need to investigate a recent security incident. To do this, you need to gather information about login attempts made after a certain date.

**Now**, based on your first query, you find a need to expand the date range to include 2022-05-09 in your search.

### Task 2. Retrieve Logins in a Date Range
In this task, you need to narrow the focus of the search. Login attempts made after 2022-05-11 shouldn't be included. Use the `BETWEEN` and `AND` operators to return results between `'2022-05-09'` and `'2022-05-11'`.

### Task 3. Investigate logins at certain times
In this task, you need to investigate logins that were made at certain times. To do this, filter the data in the log_in_attempts table by login time (login_time).

**First**, your organization's typical work hours begin at 07:00:00. Retrieve all login attempts made before 07:00:00 to learn more about the users who are logging in outside of typical hours.

### Task 4. Investigate Logins by Event ID
In this task, you need to investigate login attempts based on event ID numbers. With this query, you want to return only the event_id, username, and login_date fields from the log_in_attempts table.

### Expectations
By completing this activity, you will:

1. Gain practical experience applying:
* The `WHERE` keyword.
* The `BETWEEN` and `AND` operators.
* Operators for working with numeric or date and time data types (e.g., `=`, `>`, `>=`).
2. Build the skills needed to filter data from a table effectively.
3. Be ready to filter for numbers and dates to extract all sorts of useful information.

# 13. Filter with AND, OR, and NOT

> Please visit this [link](https://www.coursera.org/learn/linux-and-sql?specialization=google-cybersecurity) for further information.

## Scenario

In this scenario, you need to obtain specific information about employees, their machines, and the departments they belong to from the database.

Your team needs data to investigate potential security issues and to update computers.

You are responsible for filtering the required information from the database.

Here’s how you’ll do this task: **First**, you’ll retrieve all failed login attempts after business hours. **Second**, you’ll retrieve all login attempts that occurred on specific dates. **Third**, you’ll retrieve logins that didn't originate in Mexico. **Fourth**, you’ll retrieve information about certain employees in the Marketing department. **Fifth**, you’ll retrieve information about employees in the Finance or the Sales department. **Finally**, you’ll obtain information about employees who are not in the Information Technology department.

### Task 1. Retrieve After Hours Failed Login Attempts
Your team is investigating failed login attempts that were made after business hours. You want to retrieve this information from the login activity. You’ll identify all unsuccessful attempts after 18:00.

The `login_time` column in the `log_in_attempts` table contains information on when login attempts were made. Office hours end at `'18:00'`.

The `success` column in the `log_in_attempts` table contains values of `TRUE` or `FALSE` to indicate whether the login was successful. MySQL stores Boolean values as `1` for `TRUE`, and `0` for `FALSE`. This means that `TRUE` is represented as `1`, and `FALSE` represented as `0` in the `success` column.

### Task 2. Retrieve Login Attempts on Specific Dates
Your team is investigating a suspicious event that occurred on `'2022-05-09'`. You want to retrieve all login attempts that occurred on this day and the day before (`'2022-05-08'`).

The `login_date column` in the `log_in_attempts` table contains information on the dates when login attempts were made. 

### Task 3. Retrieve Login Attempts Outside of Mexico
Now, your team is investigating logins that did not originate in Mexico, and you need to find this information. Note that the country field includes entries with `'MEX'` and `'MEXICO'`. You should use the `NOT` and `LIKE` operators and the matching pattern `'MEX%'`.

### Task 4. Retrieve Employees in Marketing
For tasks 4, 5 and 6 you need to retrieve the information from the `department` and `office` columns in the `employees` table. 

Your team is updating employee machines, and you need to obtain the information about employees in the `'Marketing'` department who are located in all offices in the East building (such as `'East-170'` or `'East-320'`).

### Task 5. Retrieve Employees in Finance or Sales
Now, your team needs to perform a different update to the computers of all employees in the Finance or the Sales department, and you need to locate information on these employees. 

### Task 6. Retrieve All Employees not in IT
Your team needs to make one more update. This update was already made to employee computers in the Information Technology department. The team needs information about employees who are not in that department. You should use the `NOT` operator to identify these employees. 

### Expectations
By completing this activity, you will:

1. Gain practical experience in using SQL to:
* Run SQL queries to retrieve information from a database.
* Apply AND, OR, and NOT operators to filter SQL queries.
2. Take an important step toward running complex SQL queries to extract specific data from a database.

# 14. Applying Filters to SQL Queries  

> Please visit this [link](https://www.coursera.org/learn/linux-and-sql?specialization=google-cybersecurity) for further information.

## Scenario 

You are a security professional at a large organization. Part of your job is to investigate security issues to help keep the system secure. You recently discovered some potential security issues that involve login attempts and employee machines.

Your task is to examine the organization’s data in their **employees** and **log_in_attempts** tables. You’ll need to use SQL filters to retrieve records from different datasets and investigate the potential security issues.

**Note:** This scenario involves the same queries as the ones the **Filter with AND, OR, and NOT** lab. You can revisit the lab to get screenshots to include in your portfolio document. If you choose, it's also possible to complete this activity without revisiting the lab by typing your queries in the template.

### Step 1. Access the Template

To use the template for this course item:

Click the following link and select Use Template: [Apply filters to SQL queries](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/Apply%20filters%20to%20SQL%20queries.pdf) (In this step, you will just open the template. More instructions for how to use the template will be included in later steps.)

### Step 2. Access Supporting Materials

The following supporting materials will help you complete this activity. Keep them open as you proceed to the next steps. 

***Note:**  It is recommended that you use the **Filter with AND, OR, and NOT** lab to complete this portfolio activity.*

To use the supporting materials for this course item, click the following links:

* The Instructions for including SQL queries document provides instructions and best practices for including samples of SQL queries in your portfolio activity: [Instructions for including SQL queries](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/Instructions%20for%20including%20SQL%20queries.pdf)

* The Table formats document describes how the tables used for this portfolio activity are organized: [Table formats](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/Table%20formats.pdf)

### Step 3. Retrieve After Hours Failed login Attempts

You recently discovered a potential security incident that occurred after business hours. To investigate this, you need to query the **log_in_attempts** table and review after hours login activity. Use filters in SQL to create a query that identifies all failed login attempts that occurred after 18:00. (The time of the login attempt is found in the **login_time** column. The **success** column contains a value of **0** when a login attempt failed; you can use either a value of **0** or **FALSE** in your query to identify failed login attempts.)

Describe your query and how it works in the Retrieve after hours failed login attempts section of the Apply filters to SQL queries template. 

In the **Filter with AND, OR, and NOT** lab, take a screenshot of the SQL query you used and copy it into the template. Or, type this query directly into the template.

### Step 4. Retrieve Login Attempts on Specific Dates

A suspicious event occurred on 2022-05-09. To investigate this event, you want to review all login attempts which occurred on this day and the day before. Use filters in SQL to create a query that identifies all login attempts that occurred on 2022-05-09 or 2022-05-08. (The date of the login attempt is found in the **login_date** column.)

Describe your query and how it works in the Retrieve login attempts on specific dates section of the Apply filters to SQL queries template. 

In the **Filter with AND, OR, and NOT** lab, take a screenshot of the SQL query you used and copy it into the template. Or, type this query directly into the template.

### Step 5. Retrieve Login Attempts outside of Mexico

There’s been suspicious activity with login attempts, but the team has determined that this activity didn't originate in Mexico. Now, you need to investigate login attempts that occurred outside of Mexico. Use filters in SQL to create a query that identifies all login attempts that occurred outside of Mexico. (When referring to Mexico, the **country** column contains values of both **MEX** and **MEXICO**, and you need to use the **LIKE** keyword with % to make sure your query reflects this.)

Describe your query and how it works in the Retrieve login attempts on specific dates section of the Apply filters to SQL queries template. 

In the **Filter with AND, OR, and NOT** lab, take a screenshot of the SQL query you used and copy it into the template. Or, type this query directly into the template.

### Step 6. Retrieve Employees in Marketing

Your team wants to perform security updates on specific employee machines in the Marketing department. You’re responsible for getting information on these employee machines and will need to query the **employees** table. Use filters in SQL to create a query that identifies all employees in the Marketing department for all offices in the East building.

(The department of the employee is found in the **department** column, which contains values that include **Marketing**. The office is found in the office column. Some examples of values in this column are **East-170**, **East-320**, and **North-434**. You’ll need to use the LIKE keyword with % to filter for the East building.)

Describe your query and how it works in the Retrieve employees in Marketing section of the Apply filters to SQL queries template. 

In the **Filter with AND, OR, and NOT** lab, take a screenshot of the SQL query you used and copy it into the template. Or, type this query directly into the template.

### Step 7. Retrieve Employees in Finance or Sales

Your team now needs to perform a different security update on machines for employees in the Sales and Finance departments. Use filters in SQL to create a query that identifies all employees in the Sales or Finance departments. (The department of the employee is found in the **department** column, which contains values that include **Sales** and **Finance**.)

Describe your query and how it works in the Retrieve employees in Finance or Sales section of the Apply filters to SQL queries template. 

In the **Filter with AND, OR, and NOT** lab, take a screenshot of the SQL query you used and copy it into the template. Or, type this query directly into the template.

### Step 8. Retrieve all Employees not in IT

Your team needs to make one more update to employee machines. The employees who are in the Information Technology department already had this update, but employees in all other departments need it. Use filters in SQL to create a query which identifies all employees not in the IT department. (The department of the employee is found in the **department** column, which contains values that include **Information Technology**.)

Describe your query and how it works in the Retrieve all employees not in IT section of the Apply filters to SQL queries template. 

In the **Filter with AND, OR, and NOT** lab, take a screenshot of the SQL query you used and copy it into the template. Or, type this query directly into the template.

### Step 9. Finalize your Document

To finalize the document and make its purpose clear to potential employers, be sure to complete the Project description and Summary sections of the Apply filters to SQL queries template. 

In the Project description section, give a general overview of the scenario and what you accomplish through SQL. Write two to four sentences.

In the Summary section, provide a short summary of the previous tasks and connect them to the scenario. Write approximately two to four sentences.

### What to Include in Your Response

* Be sure to include the following in your completed activity:

* Screenshots of your queries or typed versions of the queries

* Explanations of your queries

* A project description at the beginning

* A summary at the end

* Details on using **LIKE** to search for a pattern

* Details on filtering for dates and times

* Details on using **AND** and **OR** to filter on multiple conditions

* Details on using **NOT** in filters

# 15. Using SQL Joins to Obtain Precise Data   

> Please visit this [link](https://www.coursera.org/learn/linux-and-sql?specialization=google-cybersecurity) for further information.

## Scenario 

In this scenario, you’ll investigate a recent security incident that compromised some machines.

You are a security professional at a large organization. You’ll investigate a recent security incident that compromised some machines.

You are responsible for getting the required information from the database for the investigation.

Here’s how you’ll do this task: **First**, you’ll use an inner join to identify which employees are using which machines. **Second**, you’ll use left and right joins to find machines that do not belong to any specific user and users who do not have any specific machine assigned to them. **Finally**, you’ll use an inner join to list all login attempts made by all employees.

### Task 1. Match Employees to their Machines

1. First, you must identify which employees are using which machines. The data is located in the **machines** and **employees** tables.

2. Link the joined tables on a common column. In the case of the `employees` and `machine`s tables, the `device_id` column is common.

### Task 2. Return More Data

You now must return the information on all machines and the employees who have machines. Next, you must do the reverse and retrieve the information of all employees and any machines that are assigned to them.

To achieve this, you’ll complete a left join and a right join on the **employees** and **machines** tables. The results will include all records from one or the other table. You must link these tables using the common **device_id column**.

### Task 3. Retrieve Login Attempt Data

To continue investigating the security incident, you must retrieve the information on all employees who have made login attempts. To achieve this, you’ll perform an inner join on the `employees` and `log_in_attempts` tables, linking them on the common `username` column.

### Expectations

By completing this activity, you will:

1. Develop the ability to use joins to combine data from multiple tables in a database.
2. Gain practical experience in using:
* `INNER JOIN`.
* `LEFT JOIN`.
* `RIGHT JOIN`.
3. Build confidence in using SQL joins to obtain the precise data you need.
