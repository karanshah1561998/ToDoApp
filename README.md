# ToDo App

This is a simple and interactive **ToDo Application** built using **React**. The app helps users manage tasks efficiently by providing features to add, edit, mark as complete, and persist tasks across sessions. The core functionality includes task management and state persistence using the browser's local storage.

## Live Demo

You can view the live app on Netlify: [ToDo App](https://karanshah-todoapp-v1.netlify.app/)

## Features

1. **Add New Tasks**
   - Users can add tasks through the input field and click **Add** or press **Enter** to insert the task into the list.
   
2. **Display All Tasks**
   - All tasks are displayed in a clean and simple interface.
   - A counter below the list shows the total number of tasks added.

3. **Mark Tasks as Completed**
   - Users can check the checkbox next to any task to mark it as completed. Completed tasks will be visually differentiated (e.g., with a strikethrough or color change).

4. **Edit Tasks**
   - Tasks can be edited by clicking on the task text. The task text turns into an input field, allowing you to modify the task.
   - Press **Enter** to save the changes, or click outside the field to discard the changes.

5. **Task Persistence**
   - The app uses **localStorage** to persist tasks. This means that even when the page is refreshed, tasks previously added will remain in the list.

6. **Delete All Tasks**
   - There is a button to delete all tasks from the list and reset the task count to zero.

## How to Use

- Type a task into the input field and press **Enter** or click **Add** to add the task to the list.
- Check the checkbox next to a task to mark it as completed.
- Click on a task to edit its text and press **Enter** to save changes.
- Press the **Delete All** button to clear all tasks.

## Installation Instructions

To run the app locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/karanshah1561998/TodoApp
2. **Install Dependencies: Navigate to the cloned repository's directory and run:**
   ```bash
   npm install
3. **Run the App: After the dependencies are installed, start the app using:**
   ```bash
   npm start

## Technologies Used
- React: Frontend JavaScript framework for building interactive UIs.
- CSS: For basic styling of the application.

## Future Enhancements
- Add the ability to delete individual tasks.
- Introduce task categories or priorities.
- Add due dates or deadlines for tasks.
- Implement a dark mode for a better user experience.
