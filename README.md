Features

Add and delete tasks
Mark tasks as completed with checkboxes
Filter tasks (All, Active, Completed)
Real-time statistics (Total, Completed, Remaining)
Clear all completed tasks
Delete all tasks
Data persistence using localStorage
Responsive design for mobile devices
Smooth animations and transitions

Files

TDList.html - Main page structure with input, filters, and task list
TDList.js - Task management logic, filtering, and localStorage
TDList.css - Styling, animations, and responsive layout

How to Use

Open TDList.html in a web browser
Type a task in the input field and click "Add Task" or press Enter
Click the checkbox to mark a task as completed
Use filter buttons to view All, Active, or Completed tasks
Click "Delete" button to remove individual tasks
Click "Clear Completed" to remove all finished tasks
Click "Delete All" to remove all tasks
Tasks are automatically saved and will persist after closing the browser

Customization
Change Colors
Edit in TDList.css:
css.add-btn {
    background-color: #3498db;  /* Add button color */
}

.stat-value {
    color: #3498db;  /* Statistics color */
}

.delete-btn {
    background-color: #e74c3c;  /* Delete button color */
}
Modify Statistics Display
Edit the stats section in TDList.html to add/remove statistics.
Change Storage Key
Edit in TDList.js:
javascriptconst STORAGE_KEY = 'todos';  // Change to your preferred key
Installation

Download all three files
Place them in the same folder
Open TDList.html in any browser

Browser Compatibility
Works on Chrome, Firefox, Safari, Edge, and Opera with localStorage support.
