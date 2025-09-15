# ASPNET-Week-4

Added a model for books with instance variables ID, Title, IsRead, and Ranking. Scaffolded the model to create the BooksController.

Added new Database Context for the Books model.

Migrated the books model to the database and used the "Update-Database" command. 

Added new option "Book List" on the header, routed to the Books Index page.

Added checkbox form to "Books/Index" for displaying if you have read the book.

Added a range form to "Books/Index" for displaying the rank of the book on the database.

Created a view component called "WelcomeMessage" that displays a welcome message and a total on how many books are in the database.

Copilot: Helped me with the getting access to "MvcBookContext" in the "WelcomeMessage" component. 
