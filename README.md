# Introduction
A C# .NET backend application to manage a list of books in a library.

# Prerequisites
* NET Core SDK installed on your machine.

# Open Folders
1.  Open the [BooksManagementSystem] folder and run the solution file.
2.  Add an existing project [BooksManagement_nUnitTests] to the project

# Build the Application
1.	Open a terminal or command prompt.
2.	Navigate to the root directory of the application.
3.	Run the following command to restore dependencies:

    ---[dotnet restore]---

4.	Run the following command to build the application:

	---[dotnet build]---

# Run the Application
1.	Open a terminal or command prompt.
2.	Navigate to the root directory of the application.
3.	Run the following command to start the application:

	---[dotnet run]---

4.	Follow the prompts to interact with the Book Management System.	

# Run Unit Tests
1.	Open a terminal or command prompt.
2.	Navigate to the root directory of the application.
3.	Run the following command to run the unit tests:

	---[dotnet test]---
	
4.	The tests should run, and their results will be displayed in the terminal.

# Note
The data persistence feature uses a simple JSON file-based storage system, so the application creates a JSON file named "BooksData.json" in the folder named “Data” to store the books data.
