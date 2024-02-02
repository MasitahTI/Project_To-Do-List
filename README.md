# To-Do-List
A simple system using HTML, CSS, and JavaScript without a database.

Here is a brief description of the JavaScript code:

1. **Event Listener for the "Add" Button:**
   - Obtains a reference to the "Add" button using `getElementById`.
   - Adds an event listener to invoke the `addToDoItem` function when the button is clicked.
   - The `addToDoItem` function displays a simple notification through an alert when the "Add" button is clicked.

2. **Function `newToDoItem`:**
   - Creates a new `li` element for each new task item.
   - Configures the element according to the text and completion status.
   - Appends the task element to the list (`toDoList`).
   - Adds an event listener to detect double-clicks on tasks and calls the `toggleToDoItemState` function.

3. **Function `addToDoItem` (again):**
   - Retrieves the value from the input box to add a new task.
   - Calls `newToDoItem` with the task value and completion status set to `false`.

4. **Function `toggleToDoItemState`:**
   - Allows users to toggle the completion status of a task with a double-click.
   - Utilizes the `completed` class to indicate that the task has been completed.

5. **Function `clearCompletedToDoItems`:**
   - Removes all completed tasks from the list.

6. **Function `emptyList`:**
   - Clears all tasks from the list, both completed and incomplete.

7. **Array and Local Storage Usage:**
   - Creates an array (`myArray`) and stores some elements within it.
   - Uses the `toDoInfo` object to store information about a task.
   - The `saveList` function stores the list of tasks in Local Storage using `localStorage.setItem`.
   - The `loadList` function checks Local Storage and loads previous tasks if any.

8. **Automatic List Loading:**
   - Automatically calls the `loadList` function each time the page loads to ensure task lists are restored from Local Storage.

In conclusion, this forms a To-Do List application that allows users to add, delete selected items, clear all items, and save the task list.

![Capture](https://github.com/MasitahTI/Project_To-Do-List/assets/158447847/cecfda8c-a987-49d8-aeb0-810894ca54e4)
