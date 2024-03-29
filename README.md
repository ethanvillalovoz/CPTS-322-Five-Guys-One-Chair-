#CPTS_322_PROJECT

Software Engineering Principles I Course Project

Project Name: GPTask

Instructor: Dr. Haipeng Cai

Contributors: Ethan Villalovoz, Roy Zabetski, Bryan Frederickson, Nicholas Santos, Ryan Aloof

Summary: The objective is to develop a software product for individuals looking to organize their tasks. Our group gained inspiration too...

Develop a task management app that incorporates ChatGPT and other key features to simplify tasks for the user.

The core features of the app are:

    Utilization of openai's chatgpt to help break down user tasks into smaller sub-tasks.

    Time tracking on individual tasks

    Speech to text

    Calendar for visual planning.

    Due Dates


# Repository and Installation setup

- Modify/Install Visual Studio 2022.
- When installing, install the ".NET Desktop Development" workload.  This will add the required compononents needed to debug WPF applications.
- Clone the repository and set the startup project to "gptask" if it is not set as the startup project by default.
- You should now be able to run and debug the project.

# App Usage

## Adding Lists
- Click "Add List", type the name of the list you wish to add and press the enter key when you're finished naming the list
- Clicking away from the input text field will cancel list creation.
- Multiple lists can be added (even lists with the same name!)
- Navigate between lists and other navigation items by clicking on the left sidebar.

## Deleting Lists
A list and all of its tasks and subtasks can be deleted by right clicking on the list you wish to delete and clicking the context menu item labelled, "Delete".

## Adding Tasks
- Tasks can be added by selecting a list and clicking "Add Item" after entering some text into the text input field
- Subtasks can be added by clicking the drop down of an already created task, entering text into the text input field, and clicking the "Add Item" button
in the subtask region.

## Deleting Tasks
- Tasks can be deleted by right clicking on a task and clicking "Delete"
- The same can be done for subtasks.

## Editing Tasks
- Not Implemented.

## Breaking down tasks
- Top-level tasks can be broken down into subtasks.  Right click on a task and select "Break down task".  A loading circle will appear indicating that the task is being broken down.  After some time, open the subtask menu for your task and five subtasks should appear that were generated by ChatGPT!

## Speech-To-Text
- Speech-To-Text can be triggered by clicking "Listen" next to the "Add Item" button.  The "Listen" button will light up indicating that Voice Input is enabled.  Once Voice Input is complete, the "Listen" button will no longer being illuminated, indicating that Voice Input has completed.  Shortly after, your processed speech should be entered as text in the text input field for adding a task.

## Calendar
- Clicking the "Calendar" button will navigate you to a page with a month-view calendar.  Currently, you can only move forward and backward between months.  Other functionality has not been implemented.

## Settings
- Clicking the "Settings" button will navigate you to a page with the ability to change the theme of the app between light and dark modes.  Other functionality has not been implemented.

## Due Dates
Not Implemented.

## Time Tracking
Not Implemented.

