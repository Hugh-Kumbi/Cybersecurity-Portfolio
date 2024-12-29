# 1.1 Using Variables in Python for Security Analysis

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Variables provide a flexible way to manage and track security information programmatically.

> Choosing the correct data type ensures efficient and clear handling of security-related tasks.

## Scenario
You are a security analyst who is responsible for writing code that will automate analysis of login attempts made to a specific device. As the first step, you'll need to create variables to keep track of information relevant to the login process. This information includes the device ID, list of approved usernames, maximum login attempts allowed per user, current login attempts made by a user, and login status.

Throughout this lab, you'll assign these variables and check the data types of the variables.

### Task 1
In your work as an analyst, imagine there is a device only users specified on an allow list can access, and its device ID is `"72e08x0"`.

In the following code cell, assign this value to a variable named `device_id`. Then, display the contents of the variable and observe the output.

### Task 2
Now that the variable `device_id` is defined, you can return its data type.

In this task, use a Python function to find the data type of the variable `device_id`. Store the data type in another variable called `device_id_type`. Then, display `device_id_type` to examine the output.

### Question 1
**Based on the output above, what do you observe about the data type of `device_id`?**

### Task 3
As you continue your work, you're provided a list of usernames of users who are allowed to access the device. The usernames with this access are `"madebowa"`, `"jnguyen"`, `"tbecker"`, `"nhersh"`, and `"redwards"`.

In this task, create a variable called `username_list`. Assign a list with the approved usernames to this variable. Then, display the value of the `username_list variable`.

### Task 4
In this task, find the data type of the `username_list`. Store the type in a variable called `username_list_type`. Then, display `username_list_type` to examine the output.

### Question 2
**Based on the output above, what do you observe about the data type of `username_list`?**

### Task 5
Now, imagine that you've been informed that the previous list is not up-to-date and that there is another employee that now has access to the device. You're given the updated list of usernames with access, including the new employee, as follows: `"madebowa"`, `"jnguyen"`, `"tbecker"`, `"nhersh"`, `"redwards"`, and `"lpope"`.

In this task, reassign the variable `username_list` to the new list. Run the code to display the list before and after it's been updated to observe the difference.

### Question 3
**Based on the output above, what do you observe about the contents of `username_list?`**

### Task 6
In this task, define a variable called `max_logins` that represents the maximum number of login attempts allowed per user. Store the value `3` in this variable. Then, store its data type in another variable called `max_logins_type`. Display `max_logins_type` to examine the output.

### Question 4
**Based on the output above, what do you observe about the data type of `max_logins`?**

### Task 7
In this task, define a variable called `login_attempts` that represents the current number of login attempts made by a user. Store the value `2` in this variable. Then, store its data type in a variable called `login_attempts_type`. Display `login_attempts_type` to observe the output.

### Question 5
**Based on the output above, what do you observe about the data type of login_attempts?**

### Task 8
In this task, you'll determine the Boolean value that represents whether the current number of login attempts a user has made is less than or equal to the maximum number of login attempts allowed.

### Question 6
**What is the output? What does this mean?**

### Task 9
This code continues to check for the Boolean value of whether `max_logins` is less than or equal to `login_attempts`. In this task, reassign other values to `login_attempts`. For example, you might choose a value that is higher than the maximum number of attempts allowed. Observe how the output changes.

### Question 7
Based on the different values you assigned to login_attempts, what did you observe about the output?

### Task 10
Finally, you can also assign a Boolean value of `True` or `False` to a variable.

In this task, you'll create a variable called `login_status`, which is a Boolean that represents whether a user is logged in. Assign `False` to this variable and store its data type in a variable called `login_status_type` and display it.

### Question 8
**Based on the output above, what do you observe about the data type of `login_status`?**

### Conclusion
**What are your key takeaways from this lab?**

# 1.2 Creating a Conditional Statement

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Conditional statements are a powerful structure.

> They help when you need to make sure conditions are met before certain actions are executed.

## Scenario

You’re working as a security analyst. First, you are responsible for checking whether a user’s operating system requires an update. Then, you need to investigate login attempts to a specific device. You must determine if login attempts were made by users approved to access this device and if the login attempts occurred during organization hours.

### Task 1

You are asked to help automate the process of checking whether a user’s operating system requires an update. Imagine that a user’s device can be running one of the following operating systems: `OS 1`, `OS 2`, or `OS 3`. While `OS 2` is up-to-date, `OS 1` and `OS 3` are not. Your task is to check whether the user’s system is up-to-date, and if it is, display a message accordingly. To do this, complete the conditional statement using the keyword if. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 2

Now try assigning the system variable to different values (`"OS 1"`, `"OS 2"`, and `"OS 3"`), run the cell, and observe what happens. Keep the conditional statement as is. Be sure to replace the `###YOUR CODE HERE ###` with your own code.

**Question 1** What happens when OS 2 is running? What happens when OS 1 is running?

### Task 3

Nothing is displayed when the system is not equal to `"OS 2"`. This is because the condition didn’t evaluate to `True`.

It would be beneficial if an alternative message is provided to them when updates are needed. In the following cell, add the appropriate keyword after the first conditional so that it will display a message that conveys that an update is needed when the `system` is not running OS 2.  Be sure to replace each `### YOUR CODE HERE ###` with your own code.

Then, set the value of the system variable to indicate that `OS 2` is running and run the cell. After observing what happens, set the value of `system` to indicate either that `OS 1` is running or that `OS 3` is running and run the cell.

**Question 2 In this setup what happens when OS 2 is running? And what happens when OS 2 is not running?**

### Task 4

This setup is still not ideal. If the variable system contains a random string or integer, the conditional above would still display update needed.

To improve the conditional, you will need to add the `elif` keyword. In the following cell, you will add two `elif` statements after the `if` statement, to create the final code. The first `elif` statement will display `update needed if system is "OS 1"`. The second elif statement will display the same message, if system is `"OS 3"`. 

Complete the second `elif` statement, and then run the cell with the variable system set to a different string each time. Observe what happens when each operating system is running. Also try assigning the system variable to some strings other than `"OS 1"`, `"OS 2"`, and `"OS 3"` (for example `"OS 4"`).

Be sure to replace each `### YOUR CODE HERE ###` with your own code.

**Question 3 Under this setup what happens when OS 2 is running? What happens when OS 1 is running? What happens when OS 3 is running? What happens when neither of those three operating systems are running?**

### Task 5

Writing code that is readable and concise is a best practice in programming.

The conditional above can be written more concisely.

In the following cell, use a logical operator to combine the two elif statements from the previous setup into one `elif` statement. Be sure to replace each `### YOUR CODE HERE ###`. Then, assign the system variable to a value and run the cell. Like you did in the previous task, use `"OS 1"`, `"OS 2"`, `"OS 3"`, and other strings.

**Question 4 What do you observe about this conditional?**

### Task 6

Now you’ll move on to the next part of your work. You’ve been asked to investigate login attempts
to a specific device. Only approved users should log on to this device.

You’ll start with two authorized users, stored in the variables `approved_user1` and `approved_user2`. You’ll need to write a conditional statement that compares those variables to a third variable, username. This will be the username of a specific user trying to log in. Be sure to replace each `### YOUR CODE HERE ###` with your own code.

### Task 7

The number of approved users has now expanded to five. Rather than storing each of the approved users’ usernames individually, it would be more concise to store them in an allow list called `approved_list`.

The in operator in Python can be used to determine whether a given value is an element of a sequence. Using the in operator in a condition can help you check whether a specific username is part of a list of approved usernames. For example, in the code below, `username in approved_list` evaluates to `True` if the value of the `username` variable is included in `approved_list`.

Complete the code in the following cell to display the same messages that you used in the previous step. When the condition evaluates to `True`, the following message will be displayed: `"This user has access to this device."` When it evaluates to `False`, the following message will be displayed: `"This user does not have access to this device."` Then, run the cell to observe its behavior. Afterwards, reassign the username variable to a username that is not approved and run the cell to observe what happens. Be sure to replace each `### YOUR CODE HERE ###` with your own code. Afterwards, reassign the `username` variable to a username that is not approved and run the cell to observe what happens.

**Question 5 What happens when an approved user tries to log in? What happens when an unapproved user tries to log in?**

### Task 8

Now you’ll write another conditional statement. This one will use a `organization_hours` variable to check if the user logged in during specific organization hours. When that condition is met, the code should display the string `"Login attempt made during organization hours."`. When that condition isn’t met, the code should display the string `"Login attempt made outside of organization hours."`.

The `organization_hours` variable will have a Boolean data type. If `organization_hours` has a Boolean value of `True`, that means the user is logged in during the specified organization hours. If `organization_hours` has a Boolean value of `False`, that means the user is not logged in during those hours. Be sure to replace each `### YOUR CODE HERE ###` with your own code before running the following cell.


**Question 6 What happens when the user logs in during organization hours? What happens when they log in outside of organization hours?**

### Task 9

The following cell assembles the code from the previous tasks. It includes the conditional statement that checks if a user is on the allow list and the conditional statement that checks if the user logged in during organization hours. 

Run the cell below a few times. Each time, enter a different combination of values for `username` and `organization_hours` to observe how that affects the output.

**Question 7 What happens when the user trying to log in is not among the approved users? What happens when the user trying to log in is among the approved users? What happens when the user tries to log in outside of organization hours?**

## Task 10

You can also provide a single message about the login attempt. To do this, you can join both conditions into a single conditional statement using a logical operator. This will make the code more concise. Examine the code in the following cell and add the missing operator that would allow for a single message. Be sure to replace each ### YOUR CODE HERE ### with your own code before running the following cell. Then run the cell, entering different combinations of information, and observe
what happens.

**Question 8 In this setup, what happens when the user trying to log in is an approved user and doing so during organization hours? What happens when the user either is not approved or attempts to log in outside of organization hours?**

## Conclusion
**What are your key takeaways from this lab?**

# 1.3 Creating Loops

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

## Scenario

You're working as a security analyst, and you're writing programs in Python to automate displaying messages regarding network connection attempts, detecting IP addresses that are attempting to access restricted data, and generating employee ID numbers for a Sales department.

### Task 1

In this task, you'll create a loop related to connecting to a network.  

Write an iterative statement that displays `Connection could not be established` three times. Use the `for` keyword, the `range()` function, and a loop variable of `i`. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell. 

### Task 2

The `range()` function can also take in a variable. To repeat a specified action a certain number of times, you can first assign an integer value to a variable. Then, you can pass that variable into the `range()` function within a `for` loop.

In your code that displays a network message connection, incorporate a variable called `connection_attempts`. Assign the positive integer of your choice as the value of that variable and fill in the missing variable in the iterative statement. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell. Test out the code with different values for `connection_attempts` and observe what happens. 

### Task 3

This task can also be achieved with a `while` loop. Complete the `while` loop with the correct code to instruct it to display `"Connection could not be established."` three times.

In this task, a `for` loop and a `while` loop will produce similar results, but each is based on a different approach. (In other words, the underlying logic is different in each.) A `for` loop terminates after a certain number of iterations have completed, whereas a `while` loop terminates once it reaches a certain condition. In situations where you do not know how many times the specified action should be repeated, `while` loops are most appropriate. 

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

#### **Question 1**
**What do you observe about the differences between the `for` loop and the `while` loop that you wrote?**

### Task 4

Now, you'll move onto your next task. You'll automate checking whether IP addresses are part of an allow list. You will start with a list of IP addresses from which users have tried to log in, stored in a variable called `ip_addresses`. Write a `for` loop that displays the elements of this list one at a time. Use `i` as the loop variable in the `for` loop.

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 5

You are now given a list of IP addresses that are allowed to log in, stored in a variable called `allow_list`. Write an `if` statement inside of the `for` loop. For each IP address in the list of IP addresses from which users have tried to log in, display `"IP address is allowed"` if it is among the allowed addresses and display `"IP address is not allowed"` otherwise.

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 6

Imagine now that the information the users are trying to access is restricted, and if an IP address outside the list of allowed IP addresses attempts access, the loop should terminate because further investigation would be needed to assess whether this activity poses a threat. To achieve this, use the `break` keyword and expand the message that is displayed to the user when their IP address is not in `allow_list` to provide more specifics. Instead of `"IP address is not allowed"`, display `"IP address is not allowed. Further investigation of login activity required"`.

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 7

You'll now complete another task. This involves automating the creation of new employee IDs.

You have been asked to create employee IDs for a Sales department, with the criteria that the employee IDs should all be numbers that are unique, divisible by 5, and falling between 5000 and 5150. The employee IDs can include both 5000 and 5150.

Write a while loop that generates unique employee IDs for the Sales department by iterating through numbers and displays each ID created.

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

### Task 8

You would like to incorporate a message that displays Only 10 valid employee ids remaining as a helpful alert once the loop variable reaches 5100.

To do so, include an if statement in your code.

Be sure to replace the ### YOUR CODE HERE ### with your own code before you run the following cell.

#### **Question 2**
**Why do you think the statement `print(i)` is written before the conditional rather than inside the conditional?**

### Conclusion
**What are your key takeaways from this lab?**

# 1.4 Defining and Calling a Function

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

## Scenario

Writing functions in Python is a useful skill in your work as a security analyst. In this lab, you'll define and a call a function that displays an alert about a potential security issue. Also, you'll work with a list of employee usernames, creating a function that converts the list into one string.

### Task 1

The following code cell contains a user-defined function named `alert()`. 

For this task, analyze the function definition, and make note of your observations. 

You won't need to run the cell in order to answer the question that follows. But if you do run the cell, note that it will not produce an output because the function is just being defined here.

#### **Question 1**
Summarize what the user-defined function above does in your own words. Think about what the output would be if this function were called.

### Task 2

For this task, call the `alert()` function that was defined earlier and analyze the output. 

Be sure to replace the `### YOUR CODE HERE ###` with your own code before running the following cell.

#### **Question 2**
What are the advantages of placing this code in a function rather than running it directly?

### Task 3

Functions can include other components that you've already worked with. The following code cell contains a variation of the `alert()` function that now uses a `for` loop to display the alert message multiple times.

For this task, call the new `alert()` function and observe the output. 

Be sure to replace the `### YOUR CODE HERE ###` with your own code before running the following cell.

#### **Question 3**
How does the output above compare to the output from calling the previous version of the `alert()` function? How are the two definitions of the function different?

### Task 4

In the next part of your work, you're going to work with a list of approved usernames, representing users who can enter a system. You'll be developing a function that helps you convert the list of approved usernames into one big string. Structuring this data differently enables you to work with it in different ways. For example, structuring the usernames as a list allows you to easily add or remove a username from it. In contrast, structuring it as a string allows you to easily place its contents into a text file.  

For this task, start defining a function named `list_to_string()`. Write the function header. 

Be sure to replace the `### YOUR CODE HERE ###` with your own code. Note that running this cell will produce an error since this cell will just contain the function header; you'll write the function body and complete the function definition in a later task.

### Task 5

Now you'll begin to develop the body of the `list_to_string()` function.  

In the following code cell, you're provided a list of approved usernames, stored in a variable named `username_list`. Your task is to complete the body of the `list_to_string()` function. Recall that the body of a function must be indented. To complete the function body, write a loop that iterates through the elements of the `username_list` and displays each element. Then, call the function and run the cell to observe what happens. 

Be sure to replace each `### YOUR CODE HERE ###` with your own code before running the following cell.

#### **Question 4**
What do you observe from the output above?

### Task 6

String concatenation is a powerful concept in coding. It allows you to combine multiple strings together to form one large string, using the addition operator (`+`). Sometimes analysts need to merge individual pieces of data into a single string value. In this task, you'll use string concatenation to modify how the `list_to_string()` function is defined.

In the following code cell, you're provided a variable named `sum_variable` that initially contains an empty string. Your task is to use string concatenation to combine the usernames from the `username_list` and store the result in `sum_variable`.

In each iteration of the `for` loop, add the current element of `username_list` to `sum_variable`. At the end of the function definition, write a `print()` statement to display the value of `sum_variable` at that stage of the process. Then, run the cell to call the `list_to_string()` function and examine its output.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before running the following cell.

#### **Question 5**
What do you observe from the output above?

### Task 7

In this final task, you'll modify the code you wrote previously to improve the readability of the output. 

This time, in the definition of the `list_to_string()` function, add a comma and a space (`", "`) after each username. This will prevent all the usernames from running into each other in the output. Adding a comma helps clearly separate one username from the next in the output. Adding a space following the comma as an additional separator between one username and the next makes it easier to read the output. Then, call the function and run the cell to observe the output.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before running the following cell.

#### **Question 6**
What do you notice about the output from the function call this time?

### Conclusion
**What are your key takeaways from this lab?**

# 1.5 Creating More Functions

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

## Scenario

In your work as a security analyst, you're responsible for working with a list that contains the number of failed attempts that occurred each month. You'll identify any patterns that might indicate malicious activity. You're also responsible for defining a function that compares the logins for the current day to an average and improving it by adding a `return` statement.

### Task 1
In your work as an analyst, imagine that you're provided a list of the number of failed login attempts per month, as follows: 

`119`, `101`, `99`, `91`, `92`, `105`, `108`, `85`, `88`, `90`, `264`, and `223`.

This list is organized in chronological order of months (January, February, March, April, May, June, July, August, September, October, November, and December).

This list is stored in a variable named `failed_login_list`. 

In this task, use a built-in Python function to order the list. You'll pass the call to the function that sorts the list directly into the `print()` function. This will allow you to display and examine the result.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

#### **Question 1**
**What do you observe from the output above? Do you notice any outlying numbers that indicate an increase in the failed number of login attempts?**

### Task 2
Now, you'll want to isolate the highest number of failed login attempts so you can later investigate information about the month when that highest value occurred.

You'll use the function that returns the largest numeric element from a list. Then, you'll pass this function into the `print()` function to display the result. This will allow you to determine which month to investigate further.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

#### **Question 2**
**What do you observe from the output above?**

### Task 4
Now that you've defined the `analyze_logins()` function, call it to test out how it behaves.

Call `analyze_logins()` with the arguments `"ejones"` and `9`.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

#### **Question 3**
**What does this function display? Would the output vary for different users?**

### Task 5

Now, you'll need to expand this function so that it also provides the average number of login attempts made by the user on that day. Doing this will require incorporating a third parameter into the function definition.

In this task, add a parameter called `average_day_logins`. The code will use this parameter to display an additional message. The additional message will convey the average login attemps made by the user on that day. Then, call the function with the same first and second arguments as used in Task 4 and a third argument of `3`.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 6
In this task, you'll further expand the function. Include a calculation to get the ratio of the logins made on the current day to the logins made on an average day. Store this in a new variable named `login_ratio`. The function displays an additional message that uses this variable.

Note that if `average_day_logins` is equal to `0`, then dividing `current_day_logins` by `average_day_logins` will cause an error. Due to the error, Python will display the following message: `ZeroDivisionError: division by zero`. For this activity, assume that all users will have logged in at least once before. This means that their `average_day_logins` will be greater than `0`, and the function will not involve dividing by zero.

After defining the function, call the function with the same arguments that you used in the previous task.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

#### **Question 4**
**What does this version of the `analyze_logins()` function display? Would the output vary for different users?**

### Task 7

You'll continue working with the `analyze_logins()` function and add a return statement to it. Return statements allow you to send information back to the function call.

In this task, use the `return` keyword to output the `login_ratio` from the function, so that it can be used later in your work. 

You'll call the function with the same arguments used in the previous task and store the output from the function call in a variable named `login_analysis`. You'll then use a `print()` statement to display the saved information. 

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

#### **Question 5**
**How does this version of the `analyze_logins()` function compare to the previous versions?**

### Task 8

In this task, you'll use the value of `login_analysis` in a conditional statement. When the value of `login_analysis` is greater than or equal to `3`, then the login activity will require further investigation, and an alert will be displayed. Incorporate this condition to complete the conditional statement in the code. 

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Conclusion

**What are your key takeaways from this lab?**

# 1.6 Working with Strings in Python

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

## Scenario

You’re working as a security analyst, and you are responsible for writing programs in Python to au￾tomate updating employee IDs, extracting characters from a device ID, and extracting componentsfrom a URL.

### Task 1

In your organization, employee IDs are currently either four digits or five digits in length. In this task, you’re given a four-digit numeric employee ID stored in a variable called `employee_id`. Convert this to a string format and store the result in the same variable. Later, you’ll update this employee ID string so that it complies with a new standardized format. Complete the following code. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

**Question 1 What do you observe about the data type of employee_id the first time it’s displayed? What do you observe about the data type of employee_id the second time it’s displayed (after the variable is reassigned)?**

### Task 2

Imagine that you have just been informed of a new criteria for employee IDs. They must all be five digits long for standardization purposes.

In this task, you will write a conditional statement that displays a message if the length of the employee ID is less than five digits. 

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 3

In this task, you’ll build upon the previous code. If an employee ID is only four digits, you’ll use concatenation to create a five-digit employee ID number. 

Concatenation is a process that allows you to merge strings together. The addition operator (`+`) in Python allows you to concatenate two strings.

Write an if statement that evaluates whether the length of `employee_id` is less than `5`. When the condition evaluates to `True`, reassign `employee_id` by concatenating `"E"` in front of the four-digit employee ID to create a five character employee ID. Then, display `employee_id` again. Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 4

Now you’ll move on to the next part of your task. Imagine that the characters in a device ID convey technical information about the device. You’ll need to extract characters in specific positions from the device ID. Start off by extracting the fourth character.

The variable `device_id` represents a device ID containing alphanumeric characters; it’s already stored as a string. 

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 5

Now you will also need to extract the first through the third characters in the device ID. So take a slice of the device ID. You can achieve this using bracket notation in Python. Then, display the slice to examine the result.

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 6

You’ll now proceed to the last part of your task. This involves extracting components of a URL.

You’ll work with string indices to display various components of a `URL` that’s stored in the URL variable. First, you’ll extract and display the protocol of the `URL` and the `://` characters that follow it using string slicing. Consider that the protocol is in the secure format of `https` when determining the indices for your slice.

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 7

Later in this lab, you’ll extract the domain extension. To prepare for this, use the `.index()` method to identify the index where the domain extension `.com` is located in the given `URL`.

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 8

It’s a good idea to save important data in variables when programming. This allows for quick and easy tracking and reuse of information.

Store the output of the `.index()` method in a variable called `ind`, which is short for index. This index represents the position where the domain extension `".com"` starts in the url. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell. Note that running this cell will not produce an output.

### Task 9

You can use string slicing to also extract the domain extension of a `URL`. To do so, you can create a slice. The starting index should be the `ind` variable. This contains the index where the domain extension begins. The ending index should be ind `+ 4` (since `".com"` is four characters long). Sometimes, like in this situation, it’s easier to express the ending index in relation to the starting index. Examine the following code, run it as is, and observe the output.

### Task 10

Finally, extract the website name from the given `URL` using string slicing and the ind variable that you defined earlier. In the given `URL`, the website name is `"exampleURL1"`. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Conclusion
**What are your key takeaways from this lab?**

# 1.7 Developing an Algorithm

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

## Scenario

In this lab, you're working as a security analyst and you're responsible for developing an algorithm that connects users to their assigned devices. You'll write code that indicates if a user is approved on the system and has brought their assigned device to the security team.

### Task 1

You'll work with a list of approved usernames along with a list of the approved devices assigned to these users. The elements of the two lists are synchronized. In other words, the user at index `0` in `approved_users` uses the device at index `0` in `approved_devices`. Later, this will allow you to verify if the username and device ID entered by a user correspond to each other.

First, to explore how indices in lists work, run the following code cell as is and observe the output. Then, replace each `0` with another index and run the cell to observe what happens.

#### **Question 1**
**What did you observe about the output when `approved_users[0]` is displayed and when `approved_devices[0]` is displayed? What happens when you replace each `0` with another index?**

### Task 2

There's a new employee joining the organization, and they need to be provided with a username and device ID. In the following code cell, you are given a username and device ID of this new user, stored in the variables `new_user` and `new_device`, respectively. Use the `.append()` method to add these variables to the `approved_users` and `approved_devices` respectively. Afterwards, display the `approved_users` and `approved_devices` variables to confirm the added information. Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

#### **Question 2**
**After the new approved user is added, what did you observe about the output when `approved_users` is displayed and when `approved_devices` is displayed?**

### Task 3
An employee has left the team and should no longer have access to the system. In the following code cell, you are given the username and device ID of the user to be removed, stored in the variables `removed_user` and `removed_device` respectively.  Use the `.remove()` method to remove each of these elements from the corresponding list. Afterwards, display both the `approved_users` and the `approved_devices` variables to view the removed users. Run the code and observe the results. Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

#### **Question 3**
**After the user who left the team is removed, what did you observe about the output when `approved_users` is displayed and when `approved_devices` is displayed?**

### Task 4

As part of verifying a user's identity in the system, you'll need to check if the user is one of the approved users. Write a conditional statement that verifies if a given username is an element of the list of approved usernames. If it is, display `"The user ______ is approved to access the system."`. Otherwise, display `"The user ______ is not approved to access the system."`. Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

#### **Question 4**
**What message do you observe in the output when `username` is `"sgilmore"`?**

### Task 5

The next part of the algorithm uses the `.index()` method to find the index of `username` in the `approved_list` and store that index in a variable named `ind`. 

When used on a list, the `.index()` method will return the position of the given value in the list.

Add a statement to display `ind` in the following code cell to explore the value it contains. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

#### **Question 5**
**What do you observe from the output when `username` is `"sgilmore"`?**

### Task 6

This task will allow you to build your understanding of list operations for the algorithm that you'll eventually build. It will demonstrate how you can find an index in one list and then use this index to display connected information in another list. First, use the `.index()` method again to find the index of `username` in the `approved_users` and store that in a variable named `ind`. Then, connect `ind` to the `approved_devices` and display the device ID located at the index `ind`. Afterwards, run the cell to observe the result. Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

#### **Question 6**
**What do you observe from the output when `username` is `"sgilmore"`?**

### Task 7

Your next step in creating the algorithm is to determine if a username and device ID correspond. To do this, write a conditional that checks if the `username` is an element of the `approved_devices` and if the `device_id` stored at the same index as `username` matches the `device_id` entered. You'll use the logical operator `and` to connect the two conditions. When both conditions evaluate to `True`, display a message that the username is approved and another message that the user has their assigned device. Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

#### **Question 7**
**What do you observe from the output when `username` is `"sgilmore"` and `device_id` is `"4n482ts"`?**

### Task 8

It would also be helpful for users to receive messages when their username is not approved or their device ID is incorrect.  

Add to the code by writing an `elif` statement. This `elif` statement should run when the `username` is part of the `approved_users` but the `device_id` doesn't match the corresponding device ID in the `approved_devices`. The statement should also display two messages conveying that information.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell. 

(After you run the code once with a `device_id` of `"4n482ts"`, you might want to explore what happens if you assign a different value to `device_id`.)

#### **Question 8**
**What do you observe from the output when `username` is `"sgilmore"` and `device_id` is `"4n482ts"`?**

### Task 9

In this task, you'll complete your algorithm by developing a function that uses some of the code you've written in earlier tasks. This will automate the login process.

There are multiple ways to use conditionals to automate the login process. In the following code, a nested conditional is used to achieve the goals of the algorithm. There is a conditional statement inside of another conditional statement. The outer conditional handles the case when the `username` is approved and the case when `username` is not approved. The inner conditional, which is placed inside the first `if` statement, handles the case when the `username` is approved and the `device_id` is correct, as well as the case when the `username` is approved and the `device_id` is incorrect. 

To complete this task, you must define a function named `login` that takes in two parameters, `username` and `device_id`. Afterwards, call the function and pass in different username and device ID combinations to experiment and observe the function's behavior. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

#### **Question 9**
**After Python enters the inner conditional, what happens when the `device_id` is correct, and what happens when the `device_id` is incorrect?**

### Conclusion

**What are your key takeaways from this lab?**


# 1.8 Using Regular Expressions to Find Patterns

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

## Scenario

In this lab, you're working as a security analyst and your main tasks are as follows:
- extracting device IDs containing certain characters from a log; these characters correspond with a certain operating system that requires an update.
- extracting all IP addresses from a log and then comparing them to those that are flagged in a list.

### Task 1

In order to work with regular expressions in Python, start by importing the `re` module. This module contains many functions that will help you work with regular expressions. By running the following code cell, the module will be available through the rest of the notebook.

### Task 2

In your work as a cybersecurity analyst, you're responsible for updating devices. A device ID that begins with the characters `"r15"` indicates that the device has a certain operating system that must be updated. 

You're given a log of device IDs, stored in a variable named `devices`. Your eventual goal is to extract the device IDs that start with the characters `"r15"`. For now, display the contents of the whole string to examine what it contains. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 3

In this task, you'll write a pattern to find devices that start with the character combination of `"r15"`. 

Use the regular expression symbols `\w` and `+` to create the pattern, and store it as a string in a variable named `target_pattern`.

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell. Note that the code cell will contain only variable assignments, so running it will not produce an output.

#### **Question 1**
**What regular expression pattern did you use? For each component of the pattern, what would happen if it were missing?**

### Task 4

Use the `findall()` function from the `re` module to find the device IDs that the `target_pattern` matches with. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

**Note:** In order to use `re.findall()` in Tasks 4, 7, 8, 9 and 11, you must have previously run the code `import re` in Task 1.

### Task 5

Now, the next task you're responsible for is analyzing a network security log file and determining which IP addresses have been flagged for unusual activity. 

You're given the log file as a string stored in a variable named `log_file`. There are some invalid IP addresses in the log file due to issues in data collection. Your eventual goal is to use regular expressions to extract the valid IP addresses from the string. 

Start by displaying the contents of the `log_file` to examine the details inside. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 6

In this task, you'll build a regular expression pattern that you can use later on to extract IP addresses that are in the form of xxx.xxx.xxx.xxx. In other words, you'll extract all IP addresses that contain four segments of three digits that are separated by periods.

Write a regular expression pattern that will match with these IP addresses and store it in a variable named `pattern`. Use the regular expression symbols `\d` and `\.` in your pattern. Note that the symbol `\d` matches with digits, in other words, any integer between 0 and 9. Be sure to replace the `### YOUR CODE HERE ###` with your own code. Since you'll just build the pattern here, there won't be any output when you run this cell.

### Task 7

In this task, you'll use the `re.findall()` function on the regular expression pattern stored in the `pattern` variable and the provided `log_file` to extract the corresponding IP addresses. Afterwards, run the cell and take note of what it outputs. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

#### **Question 2**
**What are some examples of IP addresses that were extracted? What are some examples of IP addresses that were not extracted? Do any that were not extracted seem to be valid IP addresses?**

### Task 8

There are some valid IP addresses in the `log_file` that you haven't extracted yet. This is because each segment of digits in a valid IP address can have anywhere between one and three digits. 

Adjust the regular expression in the `pattern` to allow for variation in the number of digits in each segment. You can do this by using the `+` symbol after the `\d` symbol. Afterwards, use the updated `pattern` to extract remaining IP addresses. Then, run the cell to analyze the results. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

#### **Question 3**
**What gets extracted here? Do all extracted IP addresses have between one and three digits in every segment?**

### Task 9

Note that all the IP addresses are now extracted but they also include invalid IP addresses with more than three digits per segment.

In this task, you'll update the `pattern` using curly brackets instead of the `+` symbol. In regular expressions, curly brackets can be used to represent an exact number of repetitions between two numbers. For example, `{2,4}` in a regular expression means between 2 and 4 occurrences of something. Applying this to an example, `\w{2,4}` would match with two, three, or four alphanumeric characters. Afterwards, you'll call the `re.findall()` function on the updated `pattern` and the `log_file` and store the output in a variable named `valid_ip_addresses`. 

Then, display the contents of `valid_ip_addresses` and run the cell to analyze the results. Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

#### **Question 4**
**What do you notice about the extracted IP addresses here compared to those extracted in the previous two tasks?**

### Task 10

Now, all of the valid IP addresses have been extracted. The next step is to identify flagged IP addresses.

You're given a list of IP addresses that have been previously flagged for unusual activity, stored in a variable named `flagged_addresses`. When these addresses are encountered, they should be investigated further. This list is just for educational purposes and contains examples of private IP addresses that are found only within internal networks.

Display this list and examine what it contains by running the cell. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 11

Task 11
Finally, you will write an iterative statement that loops through the `valid_ip_addresses` list and checks if each IP address is flagged. In the following code, the `address` will be the loop variable. Also, include a conditional that checks if the `address` belongs to the `flagged_addresses` list. If so, it should display `"The IP address ______ has been flagged for further analysis."` If not, it should display `"The IP address ______ does not require further analysis."` Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Conclusion

**What are your key takeaways from this lab?**

# 1.9 Importing and Parsing a Text File

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

## Scenario

In this lab, you're working as a security analyst. You're responsible for preparing a security log file for analysis and creating a text file with IP addresses that are allowed to access restricted information.

### Task 1
In this task, you'll import a security log text file and store it as a string to prepare it for analysis. 

In Python, a `with` statement is often used in file handling to open a file and then automatically close the file after reading it.

You're given a variable named `import_file` that contains the name of the log file that you want to import. Start by writing the first line of the `with` statement in the following code cell. Use the `open()` function, setting the second parameter to `"r"`. Note that running this code will produce an error because it will only contain the first line of the `with` statement; you'll complete this `with` statement in the task after this. Be sure to replace the `### YOUR CODE HERE ###` with your own code.

### Task 2

Now, you'll use the `.read()` method to read the imported file, and you'll store the result in a variable named `text`. Afterwards, display the `text` and explore what it contains by running the cell. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 3

The output in the previous step is one big string. In this task, you'll explore how you can split the string that contains the entire imported log file into a list of strings, one string per line. 

Use the  `.split()` method to perform this split and then display the result. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell. 

Note that displaying `.split()` doesn’t change what is stored in the `text` variable. Variable reassignment would be necessary if you want to store the result after splitting.

#### **Question 1**
**What do you notice about the output before and after using the `.split()` method?**

### Task 4

There is a missing entry in the log file. You'll need to account for that by appending it to the log file. You're given the missing entry stored in a variable named `missing_entry`. 

Use the `.write()` method and the parameter `"a"` in the `open()` function. Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

After the portion of the code that writes to the file, another with statement uses the `.read()` method to read the updated file into the `text` variable and then display it.

#### **Question 2**
**What do you notice about the position of the entry that was added to the log file?**

### Task 5

The next task you're responsible for is creating a text file. This text file should include a list of IP addresses that are allowed to access restricted information. Documenting this in a text file will help you communicate your findings to your security team. 

Start by creating a variable named `import_file` that stores the name of the file, which should be `"allow_list.txt"`. 

You're also given a variable named `ip_addresses` that stores a string containing the IP addresses that are allowed.

Run the code to display the two variables and explore what they contain. Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell. 

### Task 6

Your next goal is to create a `with` statement in order to write the IP addresses to the text file you created in the previous step. 

You'll first open the file using the `"w"` parameter. Then, you'll write the IP addresses to the file. Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell. Note that the code cell will contain a `with` statement that writes to a file but does not display information to the screen, so running it will not produce an output.

### Task 7

In this final step, you'll complete the code you've been writing up to this point. You'll add code to read the file containing IP addresses.

Complete a `with` statement that reads the text file and stores it in a new variable called `text`. 

Afterwards, display the contents of `text` and run the cell to explore the result. Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell. 

### Conclusion

**What are your key takeaways from this lab?**

# 2.1 Creating Another Algorithm

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

## Scenario

In this lab, you're working as a security analyst and you're responsible for developing an algorithm that parses a file containing IP addresses that are allowed to access restricted content and removes addresses that no longer have access.

### Task 1

Your eventual goal is to develop an algorithm that parses a series of IP addresses that can access restricted information and removes the addresses that are no longer allowed. Python can automate this process.

You're given a text file called `"allow_list.txt"` that contains a series of IP addresses that are allowed to access restricted information. 

There are IP addresses that should no longer have access to this information, and their IP addresses need to be removed from the text file. You're given a variable named `remove_list` that contains the list of IP addresses to be removed.

Display both variables to explore their contents, and run the cell. Be sure to replace each `### YOUR CODE HERE ###` with your own code before running the following cell.

#### **Question 1**
**What do you observe about the output above?**

### Task 2

In this task, start by opening the text file using the `import_file` variable, the `with` keyword, and the `open()` function with the `"r"` parameter. Be sure to replace the `### YOUR CODE HERE ###` with your own code.

For now, you'll write the first line of the `with` statement. Running this code will produce an error because it will only contain the first line of the `with` statement; you'll complete this `with` statement in the task after this.

### Task 3
Now, use the `.read()` method to read the imported file and store it in a variable named `ip_addresses`. 

Afterwards, display `ip_addresses` to examine the data in its current format. 

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

#### **Question 2**
**Do you notice any IP addresses in the allow list that are also in the `remove_list`?**

### Task 4

After reading the file, reassign the `ip_addresses` variable so its data type is updated from a string to a list. Use the `.split()` method to achieve this. Adding this step will allow you to iterate through each of the IP addresses in the allow list instead of navigating a large string that contains all the addresses merged together. 

Afterwards, display the `ip_addresses` variable to verify that the update took place.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 5

Now, you'll write code that removes the elements of `remove_list` from the `ip_addresses` list. This will require both an iterative statement and a conditional statement. 

First, build the iterative statement. Name the loop variable `element`, loop through `ip_addresses`, and display each element. Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 6

Now, build a conditional statement to remove the elements of `remove_list` from the `ip_addresses` list. The conditional statement should be placed inside the iterative statement that loops through `ip_addresses`. In every iteration, if the current element in the `ip_addresses` list is in the `remove_list`, the `remove()` method should be used to remove that element. 

Afterwards, display the updated `ip_addresses` list to verify that the elements of remove_list are no longer in the `ip_addresses`. Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 7

The next step is to update the original file that was used to create the `ip_addresses` list. A line of code containing the `.join()` method has been added to the code so that the file can be updated. This is necessary because `ip_addresses` must be in string format when used inside the `with` statement to rewrite the file.

The `.join()` method takes in an iterable (such as a list) and concatenates every element of it into a string. The `.join()` method is applied to a string consisting of the character that will be used to separate every element in the iterable once its converted into a string. In the code below, the method is applied to the string `" "`, which contains just a space character. The argument of the `.join()` method is the iterable you want to convert, and in this case, that's `ip_addresses`. As a result, it converts `ip_addresses` from a list back into a string with a space between each element and the next.

After this line with the `.join()` method, build the `with` statement that rewrites the original file. Use the `"w"` parameter when calling the `open()` function to delete the contents in the original file and replace it with what you want to write. Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell. This code cell will not produce an output.

### Task 8

In this task, you'll verify that the original file was rewritten using the correct list. 

Write another `with` statement, this time to read in the updated file. Start by opening the file. Then read the file and store its contents in the `text` variable. 

Afterwards, display the `text` variable to examine the result.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 9

The next step is to bring all of the code you've written leading up to this point and put it all into one function. 

Define a function named `update_file()` that takes in two parameters. The first parameter is the name of the text file that contains IP addresses (call this parameter `import_file`). The second parameter is a list that contains IP addresses to be removed (call this parameter `remove_list`).

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell. Note that this code cell will not produce an output.

#### **Question 3**
**What are the benefits of incorporating the algorithm into a single function?**

### Task 10

Finally, call the `update_file()` that you defined. Apply the function to `"allow_list.txt"` and pass in a list of IP addresses as the second argument.

Use the following list of IP addresses as the second argument: 

`["192.168.25.60", "192.168.140.81", "192.168.203.198"]`

After the function call, use a `with` statement to read the contents of the allow list. Then display the contents of the allow list. Run it to verify that the file has been updated by the function.

Be sure to replace the `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Conclusion

**What are your key takeaways from this lab?**


# 2.2 Updating a File Through a Python Algorithm

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

## Scenario

You are a security professional working at a health care company. As part of your job, you're required to regularly update a file that identifies the employees who can access restricted content. The contents of the file are based on who is working with personal patient records. Employees are restricted access based on their IP address. There is an allow list for IP addresses permitted to sign into the restricted subnetwork. There's also a remove list that identifies which employees you must remove from this allow list.

Your task is to create an algorithm that uses Python code to check whether the allow list contains any IP addresses identified on the remove list. If so, you should remove those IP addresses from the file containing the allow list.

Note: This scenario involves developing the same algorithm that is developed in Tasks 2-7 of the [Creating Another Algorithm Lab](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/VIII.%20Python%20Automation/2.1%20Creating%20Another%20Algorithm.ipynb). (You do not need to reference Task 1 and Tasks 8-10 of the lab to complete this portfolio activity.) You should revisit the lab to get screenshots to include in your portfolio document. 

## Step-By-Step Instructions

Follow the instructions to complete each step of the activity. 

### Step 1: Access the Template

To use the template for this course item, click the link and select Use Template. (In this step, you will just open the template. More instructions for how to use the template will be included in later steps.)

Link to template: [Algorithm for File Updates in Python](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/VIII.%20Python%20Automation/Algorithm%20for%20File%20Updates%20in%20Python.pdf)

### Step 2: Access Supporting Materials

The following supporting material will help you complete this activity. The document Instructions for including Python code provides instructions and best practices for including samples of Python code in your portfolio activity. Keep it open as you proceed to the next steps. 

To use the supporting material for this course item, click the link and select Use Template. 

Link to supporting material: [Instructions for Including Python Code](https://github.com/Hugh-Kumbi/Cybersecurity-Portfolio/blob/main/VIII.%20Python%20Automation/Instructions%20for%20Including%20Python%20Code.pdf)

### Step 3: Open the File That Contains the Allow List

The file that you want to open is called **`"allow_list.txt"`**. Assign a string containing this file name to the **`import_file variable`**. Then, use a **`with`** statement to open it. Use the variable **`file`** to store the file while you work **`with`** it inside the with statement.
  
Describe the Python syntax, functions, and keywords you need to accomplish this in the **Open the File That Contains the Allow List** section of the **Algorithm for File Updates in Python** template. In the **Task 2** section of **Creating Another Algorithm** lab, take a screenshot of this portion of your code. Or, type this code directly into the template.

### Step 4: Read the File Contents 

Next, use the **`.read()`** method to convert the contents of the allow list file into a string so that you can read them. Store this string in a variable called **`ip_addresses`**.

Describe the Python syntax, functions, and keywords you need to accomplish this in the **Read the File Contents** section of the **Algorithm for File Updates in Python** template. In the **Task 3** section of the **Creating Another Algorithm** lab, take a screenshot of this portion of your code. Or, type this code directly into the template.

### Step 5: Convert the String into a List

In order to remove individual IP addresses from the allow list, the IP addresses need to be in a list format. Therefore, use the **`.split()`** method to convert the **`ip_addresses`** string into a list.

Describe the Python syntax, functions, and keywords you need to accomplish this in the **Convert the String into a List** section of the **Algorithm for File Updates in Python** template. In the **Task 4** section of the **Creating Another Algorithm** lab, take a screenshot of this portion of your code. Or, type this code directly into the template.

### Step 6: Iterate through the Remove List

A second list called **`remove_list`** contains all of the IP addresses that should be removed from the **`ip_addresses`** list. Set up the header of a **`for`** loop that will iterate through the **`remove_list`**. Use **`element`** as the loop variable.

Describe the Python syntax, functions, and keywords you need to accomplish this in the **Iterate Through the Remove List** section of the **Algorithm for File Updates in Python** template. In the **Task 5** section of the **Creating Another Algorithm** lab, take a screenshot of this portion of your code. Or, type this code directly into the template.

### Step 7: Remove IP Addresses That are on the Remove List

In the body of your iterative statement, add code that will remove all the IP addresses from the allow list that are also on the remove list. First, create a conditional that evaluates if the loop variable **`element`** is part of the **`ip_addresses`** list. Then, within that conditional, apply the **`.remove()`** method to the **`ip_addresses`** list and remove the IP addresses identified in the loop variable **`element`**. 

Describe the Python syntax, functions, and keywords you need to accomplish this in the **Remove IP Addresses That are on the Remove List** section of the **Algorithm for File Updates in Python** template. In the **Task 6** section of the **Creating Another Algorithm** lab, take a screenshot of this portion of your code. Or, type this code directly into the template.

In addition, include a sentence that explains that applying the **`.remove()`** method in this way is possible because there are no duplicates in the **`ip_addresses`** list. 

### Step 8: Update the File With the Revised List of IP Addresses

Now that you have removed these IP addresses from the **`ip_address`** variable, you can complete the algorithm by updating the file with this revised list. To do this, you must first convert the **`ip_addresses`** list back into a string using the **`.join()`** method. Apply **`.join()`** to the string **`"\n"`** in order to separate the elements in the file by placing them on a new line.

Then, use another **`with`** statement and the **`.write()`** method to write over the file assigned to the **`import_file`** variable.

Describe the Python syntax, functions, and keywords you need to accomplish this in the **Update the File With the Revised List of IP Addresses** section of the **Algorithm for File Updates in Python** template. In the **Task 7** section of the **Creating Another Algorithm** lab, take a screenshot of this portion of your code. Or, type this code directly into the template.

### Step 8: Finalize Your Document

To finalize the document and make its purpose clear to potential employers, be sure to complete the **Project Description** and **Summary** sections of the **Algorithm for File Updates in Python** template. 

In the Project description section, give a general overview of the scenario and what you accomplished in Python. Write three to five sentences.

In the Summary section, provide a short summary of the algorithm by highlighting its main components. Write four to six sentences.

### What to Include in Your Response

**Be sure to address the following in your completed activity:** 

  * Screenshots of your Python code or typed versions of the code

  * Explanations of the syntax, functions, and keywords in the code

  * A project description at the beginning

  * A summary at the end

  * Details on using a with statement and the **`open()`** function in your algorithm

  * Details on using the **`.read()`** and **`.write()`** methods in your algorithm

  * Details on using the **`.split()`** method in your algorithm

  * Details on using a **`for`** loop in your algorithm

  * Details on using the **`.remove()`** method in your algorithm

# 2.3 Debugging Python Code

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

## Scenario

In your work as a security analyst, you need to apply debugging strategies to ensure your code works properly.

Throughout this lab, you'll work with code that is similar to what you've written before, but now it has some errors that need to be fixed. You'll need to read code cells, run them, identify the errors, and adjust the code to resolve the errors.

### Task 1

The following code cell contains a syntax error. In this task, you'll run the code, identify why the error is occuring, and modify the code to resolve it. (To ensure that it has been resolved, run the code again to check if it now functions properly.)

#### **Question 1**
**What happens when you run the code before modifying it? How can you fix this?**

### Task 2

In the following code cell, you're provided a list of usernames. There is an issue with the syntax. In this task, you'll run the cell, observe what happens, and modify the code to fix the issue.

#### **Question 2**
**What happens when you run the code before modifying it? How can you fix it?**

### Task 3

In the following code cell, there is a syntax error. Your task is to run the cell, identify what is causing the error, and fix it.

#### **Question 3**
**What happens when you run the code before modifying it? What is causing the syntax error? How can you fix it?**

### Task 4

In the following code cell, you're provided a `usernames_list`, a `username`, and code that determines whether the username is approved. There are two syntax errors and one exception. Your task is to find them and fix the code. A helpful debugging strategy is to focus on one error at a time and run the code after fixing each one.

#### **Question 4**
**What happens when you run the code before modifying it? What is causing the errors? How can you fix it?**

### Task 5

In this task, you'll examine the following code and identify the type of error that occurs. Then, you'll adjust the code to fix the error.

#### **Question 5**
**What happens when you run the code before modifying it? What type of error is this? How can you fix it?**

### Task 6

In this task, you'll examine the following code. The code imports a text file into Python, reads its contents, and stores the contents as a list in a variable named `ip_addresses`. It then removes elements from `ip_addresses` if they are in `remove_list`. There are two errors in the code: first a syntax error and then an exception related to a string method. Your goal is to find these errors and fix them.

#### **Question 6**
**What happens when you run the code before modifying it? What is causing the errors? How can you fix them?**

### Task 7

In this final task, there are three operating systems: OS 1, OS 2, and OS 3. Each operating system needs a security patch by a specific date. The patch date for OS 1 is `"March 1st"`, the patch date for OS 2 is `"April 1st"`, and the patch date for OS 3 is `"May 1st"`. 

The following code stores one of these operating systems in a variable named `system`. Then, it uses conditionals to output the patch date for this operating system. 

However, this code has logic errors. Your goal is to assign the `system` variable to different values, run the code to examine the output, identify the error, and fix it.

#### **Question 7**
**What happens when you run the code before modifying it? What is causing the logic errors? How can you fix them?**

### Conclusion

**What are your key takeaways from this lab?**
