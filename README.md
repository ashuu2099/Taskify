Taskify - Task Manager App
This is a simple Task Manager web application built using React and the Mantine UI library. It allows users to create, list, and delete tasks. The app supports two color schemes: light and dark mode.

Installation
To run the Task Manager app locally, you need to have Node.js and npm (Node Package Manager) installed on your machine. If you don't have them installed, you can download them from the official Node.js website: https://nodejs.org/.

Install dependencies:
npm install or npm i

Start the development server:
npm start 

The app should now be running at http://localhost:3000.

Usage
The Task Manager app allows you to manage your tasks effectively:

Create a Task
Click on the "Add Task" button in the app.
A modal will appear, prompting you to enter the details of the new task:
Task Title (required): Enter a title for the task.
Task Summary: Provide a summary of the task (optional).
Priority: Select the priority level of the task (low, medium, or high).
Click on the "Create Task" button to add the task to the list.
The modal will close, and the new task will be displayed in the tasks list.

Delete a Task
To delete a task from the list, click on the trash icon (🗑️) next to the task. The task will be removed from the list permanently.

Toggle Color Scheme
The app supports both light and dark color schemes. To switch between them, click on the icon in the top right corner (🌞 for light mode, 🌙 for dark mode).

Technology Stack
The Task Manager app is built using the following technologies:

React: A JavaScript library for building user interfaces.
Mantine: A modern React UI library with a set of customizable components and hooks for easier and faster web development.
tabler-icons-react: A library providing a collection of free icons to use in web applications.
@mantine/hooks: A set of useful React hooks for handling hotkeys and local storage operations.

Data Persistence
The app uses the browser's local storage to persist task data, ensuring that tasks are saved even after the page is refreshed or closed. The useLocalStorage hook from @mantine/hooks is utilized to manage the local storage.

Please note that local storage is limited in size (usually around 5-10 MB), so excessive data storage may result in limitations.

Contributions
Contributions to this Task Manager app are welcome! If you find any bugs or want to add new features, feel free to submit issues or pull requests to the repository.