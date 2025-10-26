Update the Book Catalog app with the ability to add and delete books. This is a major overhaul to the application.

Add two buttons for updating and deleting books below the "Add" button
Remove the delete button from the book component
Submitting the book form now adds it to the application state, which is maintained as a list of book objects
In addition to title, author, and url of the book cover, the book object should have a selected property which is a boolean.
This property can be toggled on or off upon clicking on the book.
Only one book can be selected at a time.
Clicking the "delete" button should delete the selected book.
The "update" button is a no-op for the time being.
Here is a live sample: https://yveshema.github.io/comp3170-book-catalog-v4/# COMP3170_Lab5
