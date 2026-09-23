# Python Workplace Task Assistant

A simple command-line task management application built using Python.

The program allows users to add tasks, view tasks, mark tasks as completed, and view a task summary.

## Features

* Add a new task
* Display all tasks
* Mark a task as completed
* View total, completed and pending tasks
* Exit the application
* Uses Python lists, dictionaries, loops, conditions and user input

## Technologies Used

* Python 3
* Visual Studio Code
* Command Line / Terminal

## How the Program Works

When the program starts, a menu is displayed:

```text
Press :
 1: Add task
 2: Show Task
 3: Complete Task
 4: summary
exit: Exit
```

The program calculates:

* Total number of tasks
* Number of completed tasks
* Number of pending tasks

## How to Run

### Step 1: Clone the Repository

Open a terminal and run:

```bash
git clone <repository-url>
```

### Step 2: Open the Project

Move into the project folder:

```bash
cd <project-folder>
```

### Step 3: Run the Python Program

```bash
python task_assistant.py
```

On some systems, use:

```bash
python3 task_assistant.py
```

## Example Session

```text
Press :
 1: Add task
 2: Show Task
 3: Complete Task
 4: summary
exit: Exit

1

Enter task : Learn Python
Task Added SuccessFully

1

Enter task : Practise GitHub
Task Added SuccessFully

2

[{'Learn Python': False}, {'Practise GitHub': False}]

3

Enter task to mark as complete: Learn Python
task Learn Python is completed

4

Total Task : 2
completed task : 1
pending :1

exit
```

## Project Purpose

This project demonstrates the development of a small workplace-style Python application using fundamental programming concepts. It can be used as a beginner portfolio project to demonstrate problem-solving, data structures, control flow and command-line application development.
