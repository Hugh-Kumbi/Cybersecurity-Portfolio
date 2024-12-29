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

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

# 1.5 Creating More Functions

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

## Scenario

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

# 1.6 Working with Strings in Python

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

## Scenario

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

# 1.7 Developing an Algorithm

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

## Scenario

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

# 1.8 Using Regular Expressions to Find Patterns

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

## Scenario

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

# 1.9 Importing and Parsing a Text File

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

## Scenario

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

# 2.1 Creating Another Algorithm

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

## Scenario

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

# 2.2 Updating a File Through a Python Algorithm

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

## Scenario

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

# 2.3 Debugging Python Code

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

## Scenario

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X

### Task X
