# Project Ideas
## Lab Assignment: Implementing CRUD Operations for a Book Application using ASP.NET Core Web API
Objective: The objective of this lab assignment is to create a RESTful Web API using ASP.NET Core that performs CRUD (Create, Read, Update, Delete) operations for a Book application. The assignment should be completed within 60 minutes.
Requirements:
1.	Create a new ASP.NET Core Web API project:
o	Use ASP.NET Core 6.0 or later.
o	Name the project BookAPI.
2.	Define the Book model:
o	Create a Book class with the following properties: 
	Id (int)
	Title (string)
	Author (string)
	PublicationDate (DateTime)
	Genre (string)
	Rating (double)
3.	Set up the database context:
o	Use Entity Framework Core to set up the database context.
o	Create a BookContext class that inherits from DbContext.
o	Define a DbSet<Book> property in the BookContext class.
4.	Configure the database connection:
o	Use an in-memory database for simplicity.
o	Configure the database connection in the appsettings.json file and the Startup class.
5.	Implement the CRUD operations:
o	Create a BooksController class that inherits from ControllerBase.
o	Implement the following actions: 
	GetBooks: Retrieve all books using LINQ queries.
	GetBookById: Retrieve a book by its ID using LINQ queries.
	CreateBook: Add a new book.
	UpdateBook: Update an existing book.
	DeleteBook: Delete a book by its ID.
6.	Implement LINQ queries:
o	Use LINQ queries to filter, sort, and retrieve data in the GetBooks and GetBookById actions.
o	Example LINQ queries: 
	Retrieve all books sorted by publication date.
	Retrieve books with a rating higher than a specified value.
	Retrieve books of a specific genre.
7.	Implement Microservices:
o	Split the application into multiple microservices, each responsible for a specific functionality.
o	Create separate microservices for managing books, authors, and genres.
o	Ensure that each microservice has its own database context and controller.
o	Use HTTP communication between microservices to perform CRUD operations.
8.	Implement Authorization using JWT tokens:
o	Add authentication and authorization to the API using JWT tokens.
o	Configure JWT authentication in the Startup class.
o	Protect the CRUD endpoints by requiring a valid JWT token for access.
o	Implement a login endpoint to generate JWT tokens for authenticated users.
9.	Test the API:
o	Use Postman or any other API testing tool to test the CRUD operations.
o	Ensure that all operations (Create, Read, Update, Delete) work as expected.
o	Test the authorization by accessing the endpoints with and without a valid JWT token.
Submission:
•	Submit the complete project folder as a ZIP file.
•	Include a README file with instructions on how to run the project and test the API.
Duration:
•	The assignment should be completed within 120 minutes.

