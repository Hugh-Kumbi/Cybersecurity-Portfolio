# 1.1 Using Variables in Python for Security Analysis

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Variables provide a flexible way to manage and track security information programmatically.

> Choosing the correct data type ensures efficient and clear handling of security-related tasks.

# Tips for Completing the Lab
As you navigate this lab, keep the following tips in mind:

- `### YOUR CODE HERE ###` indicates where you should write code. Be sure to replace this with your own code before running the code cell.
- Feel free to open the hints for additional guidance as you work on each task.
- To enter your answer to a question, double-click the markdown cell to edit. Be sure to replace the "[Double-click to enter your responses here.]" with your own answer.
- You can save your work manually by clicking File and then Save in the menu bar at the top of the notebook.
- You can download your work locally by clicking File and then Download and then specifying your preferred file format in the menu bar at the top of the notebook.

## Scenario
You are a security analyst who is responsible for writing code that will automate analysis of login attempts made to a specific device. As the first step, you'll need to create variables to keep track of information relevant to the login process. This information includes the device ID, list of approved usernames, maximum login attempts allowed per user, current login attempts made by a user, and login status.

Throughout this lab, you'll assign these variables and check the data types of the variables.

### Task 1
In your work as an analyst, imagine there is a device only users specified on an allow list can access, and its device ID is `"72e08x0"`.

In the following code cell, assign this value to a variable named `device_id`. Then, display the contents of the variable and observe the output.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 2
Now that the variable `device_id` is defined, you can return its data type.

In this task, use a Python function to find the data type of the variable `device_id`. Store the data type in another variable called `device_id_type`. Then, display `device_id_type` to examine the output.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Question 1
**Based on the output above, what do you observe about the data type of `device_id`?**

### Task 3
As you continue your work, you're provided a list of usernames of users who are allowed to access the device. The usernames with this access are `"madebowa"`, `"jnguyen"`, `"tbecker"`, `"nhersh"`, and `"redwards"`.

In this task, create a variable called `username_list`. Assign a list with the approved usernames to this variable. Then, display the value of the `username_list variable`.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Task 4
In this task, find the data type of the `username_list`. Store the type in a variable called `username_list_type`. Then, display `username_list_type` to examine the output.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Question 2
**Based on the output above, what do you observe about the data type of `username_list`?**

### Task 5
Now, imagine that you've been informed that the previous list is not up-to-date and that there is another employee that now has access to the device. You're given the updated list of usernames with access, including the new employee, as follows: `"madebowa"`, `"jnguyen"`, `"tbecker"`, `"nhersh"`, `"redwards"`, and `"lpope"`.

In this task, reassign the variable `username_list` to the new list. Run the code to display the list before and after it's been updated to observe the difference.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Question 3
**Based on the output above, what do you observe about the contents of `username_list?`**

### Task 6
In this task, define a variable called `max_logins` that represents the maximum number of login attempts allowed per user. Store the value `3` in this variable. Then, store its data type in another variable called `max_logins_type`. Display `max_logins_type` to examine the output.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Question 4
**Based on the output above, what do you observe about the data type of `max_logins`?**

### Task 7
In this task, define a variable called `login_attempts` that represents the current number of login attempts made by a user. Store the value `2` in this variable. Then, store its data type in a variable called `login_attempts_type`. Display `login_attempts_type` to observe the output.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Question 5
**Based on the output above, what do you observe about the data type of login_attempts?**

### Task 8
In this task, you'll determine the Boolean value that represents whether the current number of login attempts a user has made is less than or equal to the maximum number of login attempts allowed.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Question 6
**What is the output? What does this mean?**

### Task 9
This code continues to check for the Boolean value of whether `max_logins` is less than or equal to `login_attempts`. In this task, reassign other values to `login_attempts`. For example, you might choose a value that is higher than the maximum number of attempts allowed. Observe how the output changes.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Question 7
Based on the different values you assigned to login_attempts, what did you observe about the output?

Based on the output above, it is clear that the login_attempts are greater to max_logins.

### Task 10
Finally, you can also assign a Boolean value of `True` or `False` to a variable.

In this task, you'll create a variable called `login_status`, which is a Boolean that represents whether a user is logged in. Assign `False` to this variable and store its data type in a variable called `login_status_type` and display it.

Be sure to replace each `### YOUR CODE HERE ###` with your own code before you run the following cell.

### Question 8
**Based on the output above, what do you observe about the data type of `login_status`?**

### Conclusion
What are your key takeaways from this lab?

# 1.2 Xxxxxx

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

# Tips for Completing the Lab
As you navigate this lab, keep the following tips in mind:

- `### YOUR CODE HERE ###` indicates where you should write code. Be sure to replace this with your own code before running the code cell.
- Feel free to open the hints for additional guidance as you work on each task.
- To enter your answer to a question, double-click the markdown cell to edit. Be sure to replace the "[Double-click to enter your responses here.]" with your own answer.
- You can save your work manually by clicking File and then Save in the menu bar at the top of the notebook.
- You can download your work locally by clicking File and then Download and then specifying your preferred file format in the menu bar at the top of the notebook.

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

# 1.3 Xxxxxx

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

# Tips for Completing the Lab
As you navigate this lab, keep the following tips in mind:

- `### YOUR CODE HERE ###` indicates where you should write code. Be sure to replace this with your own code before running the code cell.
- Feel free to open the hints for additional guidance as you work on each task.
- To enter your answer to a question, double-click the markdown cell to edit. Be sure to replace the "[Double-click to enter your responses here.]" with your own answer.
- You can save your work manually by clicking File and then Save in the menu bar at the top of the notebook.
- You can download your work locally by clicking File and then Download and then specifying your preferred file format in the menu bar at the top of the notebook.

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

# 1.4 Xxxxxx

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

# Tips for Completing the Lab
As you navigate this lab, keep the following tips in mind:

- `### YOUR CODE HERE ###` indicates where you should write code. Be sure to replace this with your own code before running the code cell.
- Feel free to open the hints for additional guidance as you work on each task.
- To enter your answer to a question, double-click the markdown cell to edit. Be sure to replace the "[Double-click to enter your responses here.]" with your own answer.
- You can save your work manually by clicking File and then Save in the menu bar at the top of the notebook.
- You can download your work locally by clicking File and then Download and then specifying your preferred file format in the menu bar at the top of the notebook.

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

# 1.5 Xxxxxx

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

# Tips for Completing the Lab
As you navigate this lab, keep the following tips in mind:

- `### YOUR CODE HERE ###` indicates where you should write code. Be sure to replace this with your own code before running the code cell.
- Feel free to open the hints for additional guidance as you work on each task.
- To enter your answer to a question, double-click the markdown cell to edit. Be sure to replace the "[Double-click to enter your responses here.]" with your own answer.
- You can save your work manually by clicking File and then Save in the menu bar at the top of the notebook.
- You can download your work locally by clicking File and then Download and then specifying your preferred file format in the menu bar at the top of the notebook.

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

# 1.6 Xxxxxx

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

# Tips for Completing the Lab
As you navigate this lab, keep the following tips in mind:

- `### YOUR CODE HERE ###` indicates where you should write code. Be sure to replace this with your own code before running the code cell.
- Feel free to open the hints for additional guidance as you work on each task.
- To enter your answer to a question, double-click the markdown cell to edit. Be sure to replace the "[Double-click to enter your responses here.]" with your own answer.
- You can save your work manually by clicking File and then Save in the menu bar at the top of the notebook.
- You can download your work locally by clicking File and then Download and then specifying your preferred file format in the menu bar at the top of the notebook.

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

# 1.7 Xxxxxx

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

# Tips for Completing the Lab
As you navigate this lab, keep the following tips in mind:

- `### YOUR CODE HERE ###` indicates where you should write code. Be sure to replace this with your own code before running the code cell.
- Feel free to open the hints for additional guidance as you work on each task.
- To enter your answer to a question, double-click the markdown cell to edit. Be sure to replace the "[Double-click to enter your responses here.]" with your own answer.
- You can save your work manually by clicking File and then Save in the menu bar at the top of the notebook.
- You can download your work locally by clicking File and then Download and then specifying your preferred file format in the menu bar at the top of the notebook.

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

# 1.8 Xxxxxx

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

# Tips for Completing the Lab
As you navigate this lab, keep the following tips in mind:

- `### YOUR CODE HERE ###` indicates where you should write code. Be sure to replace this with your own code before running the code cell.
- Feel free to open the hints for additional guidance as you work on each task.
- To enter your answer to a question, double-click the markdown cell to edit. Be sure to replace the "[Double-click to enter your responses here.]" with your own answer.
- You can save your work manually by clicking File and then Save in the menu bar at the top of the notebook.
- You can download your work locally by clicking File and then Download and then specifying your preferred file format in the menu bar at the top of the notebook.

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

# 1.9 Xxxxxx

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

# Tips for Completing the Lab
As you navigate this lab, keep the following tips in mind:

- `### YOUR CODE HERE ###` indicates where you should write code. Be sure to replace this with your own code before running the code cell.
- Feel free to open the hints for additional guidance as you work on each task.
- To enter your answer to a question, double-click the markdown cell to edit. Be sure to replace the "[Double-click to enter your responses here.]" with your own answer.
- You can save your work manually by clicking File and then Save in the menu bar at the top of the notebook.
- You can download your work locally by clicking File and then Download and then specifying your preferred file format in the menu bar at the top of the notebook.

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

# 2.1 Xxxxxx

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

# Tips for Completing the Lab
As you navigate this lab, keep the following tips in mind:

- `### YOUR CODE HERE ###` indicates where you should write code. Be sure to replace this with your own code before running the code cell.
- Feel free to open the hints for additional guidance as you work on each task.
- To enter your answer to a question, double-click the markdown cell to edit. Be sure to replace the "[Double-click to enter your responses here.]" with your own answer.
- You can save your work manually by clicking File and then Save in the menu bar at the top of the notebook.
- You can download your work locally by clicking File and then Download and then specifying your preferred file format in the menu bar at the top of the notebook.

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

# 2.2 Xxxxxx

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

# Tips for Completing the Lab
As you navigate this lab, keep the following tips in mind:

- `### YOUR CODE HERE ###` indicates where you should write code. Be sure to replace this with your own code before running the code cell.
- Feel free to open the hints for additional guidance as you work on each task.
- To enter your answer to a question, double-click the markdown cell to edit. Be sure to replace the "[Double-click to enter your responses here.]" with your own answer.
- You can save your work manually by clicking File and then Save in the menu bar at the top of the notebook.
- You can download your work locally by clicking File and then Download and then specifying your preferred file format in the menu bar at the top of the notebook.

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

# 2.3 Xxxxxx

> Please visit this [link](https://www.coursera.org/learn/automate-cybersecurity-tasks-with-python) for further information.

> Xxxx

> Xxxxx

# Tips for Completing the Lab
As you navigate this lab, keep the following tips in mind:

- `### YOUR CODE HERE ###` indicates where you should write code. Be sure to replace this with your own code before running the code cell.
- Feel free to open the hints for additional guidance as you work on each task.
- To enter your answer to a question, double-click the markdown cell to edit. Be sure to replace the "[Double-click to enter your responses here.]" with your own answer.
- You can save your work manually by clicking File and then Save in the menu bar at the top of the notebook.
- You can download your work locally by clicking File and then Download and then specifying your preferred file format in the menu bar at the top of the notebook.

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