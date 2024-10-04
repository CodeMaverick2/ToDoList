# To Do List Application

### Overview:
This is a simple "To Do List" web application where users can create tasks, assign priority levels, edit tasks, and remove them. The app uses vanilla HTML, CSS, and JavaScript for functionality and responsiveness.

---

### Features:
1. **Add Task**: Users can create new tasks with different priority colors.
2. **Task Priority**: Four priority levels are represented by distinct colors (Red, Lightgreen, Lightpink, Lightblue).
3. **Remove Task**: Users can remove tasks by toggling the delete button and clicking on the task.
4. **Edit Task**: Tasks can be unlocked for editing and locked afterward to prevent changes.
5. **Task Filtering**: Tasks can be filtered by priority color for easy management.
6. **Responsive Design**: The application adjusts its layout for smaller screens.

---

### File Structure:
1. `index.html`: The main HTML structure of the To Do List.
2. `style.css`: The stylesheet for all visual styles.
3. `script.js`: The JavaScript file responsible for the app's logic and interactivity.

---

### How to Use:

1. **Priority Colors**: At the top of the page, four colors represent different task priorities. These can be clicked to filter tasks based on priority. Double-clicking will reset the filters.

2. **Adding a Task**:
    - Click the "Add" button (`+`) to open a modal.
    - Select a priority color from the modal, enter your task, and press "Enter."
    - The task will be added with a unique ID.

3. **Removing a Task**:
    - Click the "Trash" button to toggle the delete mode.
    - While in delete mode, click any task to remove it.

4. **Editing a Task**:
    - Click the lock icon to unlock the task and make it editable.
    - After making changes, click the unlock icon to lock the task.

---

### Key Sections in the Code:

- **HTML (`index.html`)**: 
    - Contains the structure of the toolbox, modal, and main content area where tasks appear.
    - Imports the Font Awesome icons for button icons.

- **CSS (`style.css`)**:
    - Defines styles for the app layout, buttons, priority colors, and modal appearance.
    - Adds responsive styles for screens below 768px width.

- **JavaScript (`script.js`)**:
    - Adds interactivity for adding, removing, editing, and filtering tasks.
    - Generates a unique ID for each task.
    - Handles priority color selection and task management logic.

---

### Customization:

- **Colors**: The priority colors and their associated classes (red, lightgreen, lightpink, lightblue) can be changed in both the CSS and JavaScript.
  
- **Task IDs**: The `randomID()` function can be customized to generate IDs of different lengths or characters.

---

### Setup:
To use this application, download the files and open `index.html` in any modern web browser.

---

### Future Improvements:

- Add local storage support to save tasks even after the browser is refreshed.
- Allow users to set due dates for tasks.
- Implement drag-and-drop functionality for task rearrangement.
- Add additional task filtering options (e.g., by due date or completion status).

---

### Conclusion:
This To Do List project demonstrates how a basic task management system can be created with HTML, CSS, and JavaScript, providing interactivity and a simple user interface for everyday task management.