# ToDoList
The provided Java code is an implementation of a simple command-line To-Do List application. Here's a description of the project:

1. **User Interaction**: The program interacts with the user through the console. It starts by asking the user to enter their name and welcomes them.
2. **To-Do List**: The main functionality of the program is to manage a to-do list. The user can add tasks to the list, remove tasks, and view the current tasks.
3. **Data Storage**: Tasks are stored in an array named `tasks`, and the maximum number of tasks that can be stored is defined as `MaxTasks`. The current number of tasks is tracked using the `TaskCount` variable.
4. **User Menu**: The program displays a menu of options for the user to choose from:
    - Option 1: Add a Task - The user can input a task description, which is added to the to-do list.
    - Option 2: Remove a Task - The user can specify a task number to remove from the list. The program shifts the remaining tasks to fill the gap.
    - Option 3: Exit - The user can choose to exit the program.
5. **Input Handling**: The code handles user input, such as the user's name and their choices, using the `Scanner` class.
6. **User-Friendly Interface**: The program provides a user-friendly interface, displaying the user's name, the list of tasks, and appropriate messages to guide the user through the process.
7. **Limit on Tasks**: There is a limit on the number of tasks that can be added to the list, which is `MaxTasks`. If the list is full, the program informs the user.
8. **Error Handling**: The program includes error handling for invalid inputs. It checks for task numbers when removing tasks and validates user menu choices.
9. **Looping**: The program runs in an infinite loop, allowing the user to continue adding, removing, and managing tasks until they choose to exit.
10. **Exiting the Program**: The user can choose to exit the program by selecting option 3, which terminates the application.

This simple To-Do List application provides a basic way for users to manage their tasks through the command line. Users can add and remove tasks, making it a useful tool for personal task management.
