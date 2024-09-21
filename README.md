## To-do App Documentation

This documentation describes the To-do app, a simple web application built with HTML, CSS, and JavaScript. It provides a user interface to create, manage, and mark off tasks.

### Features

*   **Add Tasks:** Users can add new tasks by typing them into an input box and pressing Enter or clicking the 'Add' button. The tasks are displayed in a list format.
*   **Mark Tasks as Complete:** Each task can be marked as complete by clicking on it. The completed tasks are visually indicated by strikethrough text and a checked icon.
*   **Delete Tasks:** Users can delete tasks by clicking on the 'X' icon next to each task.
*   **Persistence:** The application utilizes local storage to save the tasks, ensuring they are retained even after the page is refreshed or closed. 

### Usage

1.  **Open the App:** Navigate to the To-do app's website or open the `index.html` file in a web browser.
2.  **Add Tasks:** Enter the task you wish to complete in the input box and press Enter or click the 'Add' button.
3.  **Manage Tasks:** Click on a task to mark it as complete or click on the 'X' icon to delete it. 

### Files

The To-do app is composed of the following files:

*   **`index.html`:** The main HTML file that defines the structure of the app's interface.
*   **`script.js`:** The JavaScript file that handles the app's logic, including adding, marking, and deleting tasks, as well as local storage functionality. 
*   **`style.css`:** The CSS file that provides styling for the app's visual appearance.
*   **`assets/img/`:**  The folder containing the images used in the app: `check.svg`, `todo.svg`, `uncheck.svg`.

### Inputs

*   **Text Input:** The user enters tasks into the input box.

### Outputs

*   **Task List:** The app displays a list of all the tasks, including completed and incomplete tasks. 
*   **Visual Indicators:**  Completed tasks are visually indicated with strikethrough text and a checked icon.  Tasks are removed from the list when they are deleted.

### Libraries and Dependencies

The app doesn't rely on any external libraries or dependencies. It is written purely with HTML, CSS, and JavaScript. 