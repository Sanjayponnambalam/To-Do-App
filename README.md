# To-Do Application

## Overview
This project is a simple and interactive To-Do List web application that allows users to add, delete, and filter tasks. The application uses JavaScript for dynamic interactions and local storage to retain tasks across sessions.

## Key Features
- **Task Management:** Users can add, complete, and remove tasks from the list.
- **Filtering Options:** Users can filter tasks by status (All, Completed, Incomplete).
- **Local Storage Support:** Tasks are stored in the browser's local storage for persistence.
- **User-Friendly Interface:** Clean and minimalistic UI with intuitive controls.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/todo-list.git
   cd todo-list
   ```
2. Open `index.html` in your browser.

## Usage
1. Enter a task in the input field and click the `+` button to add it to the list.
2. Click the check icon to mark a task as completed.
3. Click the trash icon to remove a task.
4. Use the dropdown filter to view all, completed, or incomplete tasks.

## Architecture
### **Workflow Overview**
1. **User Input & Task Creation**: Users add tasks using the input field.
2. **Task Display & Interaction**: Tasks are dynamically displayed and can be marked as completed or deleted.
3. **Filtering Mechanism**: Users can filter tasks based on their completion status.
4. **Local Storage Management**: Tasks persist even after refreshing the page.

## Implementation Details
### **Frontend Technologies Used**
- **HTML**: Structure of the application.
- **CSS**: Styling and layout.
- **JavaScript**: Functionality and interactivity.

### **Local Storage Handling**
- Tasks are stored as an array in `localStorage`.
- Tasks are retrieved and displayed upon page load.
- Deleting a task updates `localStorage` accordingly.

## Future Enhancements
- Implement drag-and-drop functionality for task reordering.
- Add due dates and priority levels.
- Integrate with a backend to enable multi-device synchronization.
- Implement dark mode for better user experience.



