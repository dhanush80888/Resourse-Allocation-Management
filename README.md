# Resource Management System

## Overview

The Resource Management System is a command-line application written in Python designed to manage resources and tasks effectively. Users can create, update, delete, and assign resources to tasks, all while monitoring resource utilization.

## Features

- **Resource Management**: Create, read, update, and delete resources.
- **Task Management**: Create and view tasks with associated resources.
- **Resource Assignment**: Easily assign resources to tasks.
- **Utilization Monitoring**: Check the status of specific resources.
- **Interactive Menu**: User-friendly command-line interface for easy navigation.

## Requirements

- Python 3.x

## Installation

1. Clone or download the repository to your local machine.
2. Open your terminal or command prompt.
3. Navigate to the project directory.
4. Run the application with the following command:

   ```bash
   python resource_manager.py
Usage
After launching the application, a menu will appear with several options:

Create Resource: Add a new resource by specifying its ID, type, and name.
Read Resources: Display all existing resources.
Update Resource: Modify the name of an existing resource using its ID.
Delete Resource: Remove a resource by providing its ID.
Create Task: Add a new task with a unique ID and description.
Read Tasks: View all tasks along with their assigned resources.
Assign Resource to Task: Assign a specified resource to a task using their IDs.
Monitor Resource Utilization: Get details about a specific resource using its ID.
Exit: Terminate the application.
Example Workflow
Start the application.
Use option 1 to create a resource and follow the prompts.
Select option 2 to view the created resources.
Create a task using option 5 and then assign a resource with option 7.
Monitor a resource using option 8.
Exit the program using option 9.
Code Structure
Resource Class: Represents a resource with attributes like ID, type, and name.
Task Class: Represents a task with attributes such as ID, description, and a list of assigned resources.
ResourceManager Class: Handles the operations related to resources and tasks.
Contribution
Contributions are welcome! If you have suggestions for enhancements or new features, please open an issue or submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements
Python Software Foundation for the programming language.
Community resources that assisted in the development of this application.
css
Copy code

Feel free to customize this README further to suit your project needs!
