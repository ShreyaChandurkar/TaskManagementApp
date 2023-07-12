I have developed a Task Management app using Next.js 13, TypeScript, and Tailwind CSS. The app aims to provide an efficient way to manage tasks. When you click on the "Add new task" button, a Tailwind CSS modal will open, allowing you to enter the details of a new task. Each task displayed in the app is accompanied by two icons: an edit icon and a delete icon. If you click on the edit icon, you can modify the task's information. Similarly, clicking on the delete icon will remove the task from the list.

The app implements CRUD (Create, Read, Update, Delete) operations to handle the task management functionalities. This means you can create new tasks, view the existing tasks, edit their details, and delete tasks when needed. To ensure data persistence, the app stores the task information in the local storage of your browser. This way, you can access and manage your tasks even after closing or refreshing the app.

To set up and run the Task Management app on your local machine, please follow these steps:

1. Download the app's code as a zip file.
2.Extract the code and place it in a suitable folder location on your computer.
3.Open a terminal or command prompt window.
4.Use the "cd" command to navigate to the "task-management" directory in the terminal i.e. "cd task-management".
5.Install the required dependencies by running the command "npm install".
6.Start the development server using the command "npm run dev".
7.Open your web browser and enter "http://localhost:3000/" to access the Task Management app.
8.To simulate CRUD operations and data storage, open a new terminal or command prompt window.
9.Navigate to the "task-management" directory again using the "cd" command i.e. "cd task-management".
10.Run the JSON server by executing the command "npm run json-server".
11.The JSON server will be available at "http://localhost:3001/tasks".
