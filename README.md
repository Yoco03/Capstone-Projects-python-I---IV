# Capstone-Projects

### In this file you will find 4 Capstone projects with completed tasks that was done at HyperionDev.

_IDE used for these projects below - **Python**_

### **Capstone folder I**
* is a finace calculator that we need to create in python

### **Capstone folder II**
* is a py.game that we need to create in python

### **Capstone folder III**
#### Complulsory Task Part 1
* We had to creating a program for a small business that can
help it to manage tasks assigned to each member of the team. which will be an extension of our next Capstone IV.
Created a Python file called task_manager.py in this folder.

* This program will work with two text files, user.txt and tasks.txt . Open
each of the files that accompany this project.

    * **tasks.txt** stores a list of all the tasks that the team is working on.
      Open the **tasks.txt** file that accompanies this project. Note that this
      text file already contains data about two tasks. The data for each
      task is stored on a separate line in the text file. Each line includes
      the following data about a task in this order:

        * The username of the person to whom the task is assigned.
        *  The title of the task.
        *  A description of the task.
        *  The date that the task was assigned to the user.
        *  The due date for the task.
        *  Either a ‘Yes’ or ‘No’ value that specifies if the task has been
        *  completed yet.

     * **user.txt** stores the username and password for each user that has
      permission to use your program ( **task_manager.py** ). Open the
      **user.txt** file that accompanies this project. Note that this text file
      already contains one default user that has the username, ‘admin’
      and the password, ‘adm1n’. The username and password for each
      user must be written to this file in the following format:

        * First, the username followed by a comma, a space and then
            the password.
        * One username and corresponding password per line.
 


* Your program should allow your users to do the following:
        * Login. The user should be prompted to enter a username and
         password. A list of valid usernames and passwords are stored in a
         text file called **user.txt** . Display an appropriate error message if the
         user enters a username that is not listed in **user.txt** or enters a valid
         username but not a valid password. The user should repeatedly be
         asked to enter a valid username and password until they provide
         appropriate credentials.

         The following menu should be displayed once the user has
         successfully logged in:
         
![](Capstone%20Project%20III%20(Task%2020)/images/task.png)
            
            * If the user chooses ‘r’ to register a user, the user should be
            prompted for a new username and password. The user should also
            be asked to confirm the password. If the value entered to confirm
            the password matches the value of the password, the username
            and password should be written to user.txt in the appropriate
            format.

* If the user chooses ‘a’ to add a task, the user should be prompted to
enter the username of the person the task is assigned to, the title of
the task, a description of the task and the due date of the task. The
data about the new task should be written to tasks.txt . The date on
which the task is assigned should be the current date. Also assume
that whenever you add a new task, the value that indicates
whether the task has been completed or not is ‘No’.
* If the user chooses ‘va’ to view all tasks, display the information for
each task on the screen in an easy to read format.
* If the user chooses ‘vm’ to view the tasks that are assigned to them,
only display all the tasks that have been assigned to the user that is
currently logged-in in a user-friendly, easy to read manner.

#### Compulsory Task Part 2
* Now format your program so that:
   * Only the user with the username ‘admin’ is allowed to register
     users.
   * The admin user is provided with a new menu option that allows
     them to display statistics. When this menu option is selected, the
     total number of tasks and the total number of users should be
     displayed in a user-friendly manner.

### **Capstone folder IV**

#### Compulsory Task

*Follow these steps:
   * Create a copy of your previous Capstone project ( task_manager.py) and
   save it in the Dropbox folder for this project. Also, copy and paste the text
   files ( user.txt and tasks.txt ) that accompanied the previous Capstone
   project to this folder. Modify this program as follows:
   * Modify the code of your previous project so that functions are used.
   Adding functions will improve the modularity of your code. Your program
   should include at least the following functions:
      * reg_user — that is called when the user selects ‘ r ’ to register a user.
      * add_task — that is called when a user selects ‘ a ’ to add a new task.
      * view_all — that is called when users type ‘va’ to view all the tasks
        listed in ‘tasks.txt’.
      * view_mine — that is called when users type ‘vm’ to view all the
        tasks that have been assigned to them.
        
* Modify the function called reg_user to make sure that you don’t duplicate
usernames when you add a new user to user.txt . If a user tries to add a
username that already exists in user.txt , provide a relevant error message
and allow them to try to add a user with a different username.

* Add the following functionality when the user selects ‘vm’ to view all the
tasks assigned to them:
   * Display all tasks in a manner that is easy to read. Make sure that
each task is displayed with a corresponding number which can be
used to identify the task.
   * Allow the user to select either a specific task by entering a number
or input ‘-1’ to return to the main menu.
   * If the user selects a specific task, they should be able to choose to
either mark the task as complete or edit the task . If the user
chooses to mark a task as complete, the ‘Yes’/’No’ value that
describes whether the task has been completed or not should be
changed to ‘Yes’. When the user chooses to edit a task, the
username of the person to whom the task is assigned or the due
date of the task can be edited. The task can only be edited if it has
not yet been completed.
* Add an option to generate reports to the main menu of the application.
The menu for the admin user should now look something like this:






