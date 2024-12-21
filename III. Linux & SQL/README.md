# Computing Essentials: Mastering Linux and SQL for Data Handling

This folder contains exercises, solutions, and supporting materials related to foundational computing skills, focusing on using the Linux command line and querying databases with SQL. It showcases proficiency in navigating the Linux operating system for efficient system management and performing SQL queries to manage and analyze data.

## Contents
1.1 **Install Software in a Linux Distribution**
- In this lab, I used the **Advanced Package Tool (APT)** and `sudo` commands to install and manage applications in a Debian-based Linux virtual machine, focusing on network security tools like Suricata and tcpdump. Suricata serves as an intrusion detection system, while tcpdump is a packet analyzer for examining network traffic. The use of a virtual machine ensured a safe testing environment with the ability to revert changes if needed. This activity highlighted the importance of mastering Linux application management, a crucial skill for configuring and utilizing security tools effectively as a security analyst.
  
1.2 **Examine Input and Output in the Linux Shell**
- In this lab, I used the `echo` command to explore how input is received and output is returned in the Linux shell, followed by the `expr` command to perform basic calculations and further understand input and output interactions. This activity provided foundational knowledge of communicating with the Linux operating system through the shell, an essential skill for a security analyst to execute commands effectively and interpret system responses, including error messages.

1.3 **Find Files with Linux Commands**
- In this lab activity, I navigated the Linux file structure, located specific files, and read their contents using commands in the Linux shell. This exercise helped me develop essential skills for navigating, managing, and analyzing files remotely through a Linux shell, which is critical for my role as a security analyst.

1.4 **Using grep and Piping for File Searching and Data Extraction**
- In this lab, I used the grep command and piping to efficiently search through files and extract specific information. By working with various files, including server log files and user data files, I practiced retrieving targeted data. I completed these tasks using Linux commands in the Bash shell, enhancing my ability to analyze and process file contents as part of my skill set in Linux systems management.

1.5 **Managing Directory Structures and File Editing in Linux**
- In this lab, I used Linux commands to modify a directory structure and manage the files it contains. I also utilized the nano text editor to add text to a file. This activity reinforced the importance of organizing directories and files to streamline data management. As a security analyst, being able to create, remove, and edit directories and files is a crucial skill for detecting issues and maintaining data security effectively.

1.6 **Configuring Authorization and Managing Permissions in Linux**
- In this lab activity, I used Linux commands to configure authorization and manage access to system resources. I explored the concept of file and directory permissions, learning how to change ownership to control access to specific files and directories. By setting appropriate access permissions, I helped mitigate security risks by limiting unauthorized access to sensitive information. This task is a crucial skill for a security analyst, ensuring that only authorized users can access and modify critical system files, thereby maintaining the overall security of the system. 

1.7 **Portfolio Document: Demonstrating File Permission Management in Linux**
- In this activity, I created a new portfolio document showcasing my experience using Linux commands to manage file permissions. This document highlights my ability to control access to files and directories, an essential skill for ensuring system security.

1.8 **Managing User Access in Linux**
- In this lab activity, I used the  `useradd`, `usermod`, `userdel`, and `chown` commands to manage user access in the Linux Bash shell. By utilizing these commands, I was able to add, modify, and delete user accounts, as well as change file ownership to control access. Since these tasks require root (superuser) privileges, I used sudo to execute the commands. Proper management of users and their access to resources is a critical skill for a security analyst, as it helps maintain control over who can access and modify system files and data.

1.9 **Exploring Linux Command Documentation**
- In this lab activity, I explored how to get help and find information directly through the Linux command line. I used the `man` and `whatis` commands to retrieve details about specific Linux commands and their functions. Additionally, I used the `apropos` command to search manual pages for commands that match a specified string. As a security analyst, it’s essential to know how to efficiently discover relevant commands and understand their usage, ensuring I can troubleshoot issues and find solutions quickly when working in a Linux environment.

2.1 **Querying Databases with SQL: SELECT, FROM, and ORDER BY**
- In this lab activity, I used SQL commands to retrieve and organize information from a database. I applied the `SELECT` and `FROM` statements to return specific data and used the `ORDER BY` keyword to sort the query results based on a designated column. As a security analyst, knowing how to query and analyze database information is essential for identifying patterns, improving security, and ensuring data integrity.

2.2 **Filtering Numbers and Dates in SQL: Using Comparison Operators**
- In this lab activity, I worked with numeric and date-based data in SQL, using comparison operators to filter specific results effectively. I applied operators such as `=`, `>`, `<`, `<>`, `>=`, and `<=` to retrieve data based on precise conditions. For example, I filtered records to identify machines needing updates or login attempts occurring within a specific timeframe. As a security analyst, mastering these operators is critical for analyzing numerical and date-related data to identify vulnerabilities, investigate incidents, and maintain system security.

2.3 **Filtering Data with AND, OR, and NOT Operators in SQL**
- In this lab activity, I practiced creating complex SQL queries by applying the `AND`, `OR`, and `NOT` operators to filter data based on multiple conditions. I used these logical operators to refine my queries, retrieving specific information while excluding data that didn’t meet certain criteria. This exercise demonstrated how combining multiple conditions helps in pinpointing precise results, a key skill for analyzing large datasets as a security analyst. Complex queries like these are essential for investigating incidents, identifying anomalies, and improving overall data security.

2.4 **Portfolio Document: Demonstrating SQL Query Skills**
- In this activity, I created a portfolio document showcasing my experience with SQL, specifically focusing on using the `AND`, `OR`, and `NOT` operators to filter and retrieve data based on multiple conditions. I explained the queries I performed during the lab, detailing how I combined conditions to extract specific information while excluding irrelevant results. This document serves as evidence of my SQL skills and will help me prepare for job interviews and other steps in the hiring process, demonstrating my ability to analyze data effectively as a security analyst.

2.5 **Using SQL Joins to Connect Tables and Retrieve Information**
- As part of this lab activity, I used SQL joins to combine data from multiple related tables within a relational database. By leveraging shared columns, I retrieved information that spanned across different tables, enabling me to connect and analyze data efficiently. This skill is crucial for a security analyst, as it allows for a more comprehensive understanding of datasets and provides insights into patterns or issues that might not be apparent when analyzing individual tables in isolation.

***Note:** For detailed instructions, see* [Instructions](Instructions.md).

## Proposed Resolution
- **Exercise 1:** [Hugh_Application Management in Linux Using APT and Sudo](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/1.1%20Hugh_Application%20Management%20in%20Linux%20Using%20APT%20and%20Sudo.md)
- **Exercise 2:** [Hugh_Exploring Linux Shell Interactions: Understanding Input, Output, and Basic Calculations](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/1.2%20Hugh_Exploring%20Linux%20Shell%20Interactions%3A%20Understanding%20Input%2C%20Output%2C%20and%20Basic%20Calculations.md)
- **Exercise 3:** [Hugh_Mastering Linux File Navigation and Analysis for Security Operations](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/1.3%20Hugh_Mastering%20Linux%20File%20Navigation%20and%20Analysis%20for%20Security%20Operations.md)
- **Exercise 4:** [Hugh_Using grep and Piping for File Searching and Data Extraction](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/1.4%20Hugh_Using%20grep%20and%20Piping%20for%20File%20Searching%20and%20Data%20Extraction.md)
- **Exercise 5:** [Hugh_Managing Directory Structures and File Editing in Linux](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/1.5%20Hugh_Managing%20Directory%20Structures%20and%20File%20Editing%20in%20Linux.md)
- **Exercise 6:** [Hugh_Configuring Authorization and Managing Permissions in Linux](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/1.6%20Hugh_Configuring%20Authorization%20and%20Managing%20Permissions%20in%20Linux.md)
- **Exercise 7:** [Hugh_Demonstrating File Permission Management in Linux](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/1.7%20Hugh_Demonstrating%20File%20Permission%20Management%20in%20Linux.pdf)
- **Exercise 8:** [Hugh_Managing User Access in Linux](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/1.8%20Hugh_Managing%20User%20Access%20in%20Linux.md)
- **Exercise 9:** [Hugh_Exploring Linux Command Documentation](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/1.9%20Hugh_Exploring%20Linux%20Command%20Documentation.md)
- **Exercise 10:** [Hugh_Querying Databases with SQL: SELECT, FROM, and ORDER BY](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/2.1%20%20Hugh_Querying%20Databases%20with%20SQL%3A%20SELECT%2C%20FROM%2C%20and%20ORDER%20BY.md)
- **Exercise 11:** [Hugh_Filtering Data in SQL: Applying Basic Query Filters](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/2.2%20Hugh_Filtering%20Data%20in%20SQL%3A%20Applying%20Basic%20Query%20Filters.md)
- **Exercise 12:** [Hugh_Filtering Data with AND, OR, and NOT Operators in SQL](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/2.3%20Hugh_Filtering%20Data%20with%20AND%2C%20OR%2C%20and%20NOT%20Operators%20in%20SQL.md)
- **Exercise 13:** [Hugh_Filtering Numbers and Dates in SQL: Using Comparison Operators](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/2.4%20Hugh_Filtering%20Numbers%20and%20Dates%20in%20SQL%3A%20Using%20Comparison%20Operators.md)
- **Exercise 14:** [Hugh_Demonstrating SQL Query Skills](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/2.5%20Hugh_Demonstrating%20SQL%20Query%20Skills.pdf)
- **Exercise 15:** [Hugh_Using SQL Joins to Connect Tables and Retrieve Information](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/2.6%20Hugh_Using%20SQL%20Joins%20to%20Connect%20Tables%20and%20Retrieve%20Information.pdf)

## Supporting Materials
- **Apply filters to SQL queries.pdf:** [Apply filters to SQL queries](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/Apply%20filters%20to%20SQL%20queries.pdf)
- **Current file Permissions.pdf:** [Current file Permissions](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/Current%20file%20Permissions.pdf)
- **File Permissions in Linux.pdf:** [File Permissions in Linux](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/File%20Permissions%20in%20Linux.pdf)
- **Instructions for Including Linux Commands.pdf:** [Instructions for Including Linux Commands](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/Instructions%20for%20Including%20Linux%20Commands.pdf)
- **Instructions for including SQL queries.pdf:** [Instructions for including SQL queries](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/Instructions%20for%20including%20SQL%20queries.pdf)
- **Table formats.pdf:** [Table formats](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/III.%20Linux%20%26%20SQL/Table%20formats.pdf)
