Name: SRI UMA VUNDAVALLI
Company: CODTECH IT SOLUTIONS
ID: CT4FWD2931
Domain: Frontend Development
Duration: June to July 2024


OVERVIEW:
This task involves creating a simple "Todo List" web application using HTML, CSS, and JavaScript. The application allows users to add, check off, delete, and save tasks. Here's an overview of the various components and their functionalities:

HTML Structure
The HTML file sets up the structure of the todo list application, including links to Bootstrap for styling and FontAwesome for icons.

Head Section: Includes links to external CSS and JS libraries (Bootstrap, jQuery, Popper.js, FontAwesome).
Body Section: Contains the main structure of the todo list:
A container for the todo list.
Input field for adding new tasks.
Buttons for adding and saving tasks.
A list (ul) to display the tasks.
CSS Styling
The CSS styles the application, providing a clean and visually appealing layout. Key styles include:

.todos-bg-container: Sets the background color and height of the container.
Headings (.todos-heading, .create-task-heading, etc.): Style the headings for different sections of the application.
.todo-user-input: Styles the input field for adding new tasks.
.button: Styles the buttons for adding and saving tasks.
.label-container, .checkbox-input, .checkbox-label: Styles for the todo items, including the checkbox and text label.
.delete-icon: Styles the delete icon.
JavaScript Functionality
The JavaScript file contains the logic for managing the todo list, including adding, checking off, deleting, and saving tasks. Key functions and elements include:

DOM Elements: References to key DOM elements like the todo list container, add button, and save button.
Local Storage: Functions to retrieve (getTodoListFromLocalStorage) and save (saveTodoButton.onclick) the todo list from/to local storage.
Add Todo: onAddTodo function creates a new todo item and appends it to the list.
Todo Status Change: onTodoStatusChange function toggles the checked status of a todo item.
Delete Todo: onDeleteTodo function removes a todo item from the list.
Create and Append Todo: createAndAppendTodo function dynamically creates and adds a new todo item to the DOM.
Key Points
Input Validation: Ensures that the user cannot add an empty todo item.
Todo Item Structure: Each todo item is structured as a list item (li) containing a checkbox, label, and delete icon.
Dynamic Updates: Adding, checking off, and deleting todo items update the DOM and the todo list array in real-time.
Persistent Storage: The todo list is saved in local storage, allowing the user to retain their tasks across sessions.
This task effectively demonstrates a practical use of HTML, CSS, and JavaScript to create an interactive web application with persistent data storage.
![Screenshot 2024-07-24 180106](https://github.com/user-attachments/assets/fddfe65f-b507-453d-bc76-449b37a1bb34)
