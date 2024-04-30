# Text Summarizer Backend
This project is a backend application for a text summarizer service. It provides a set of RESTful APIs for managing user accounts and summarizing text content.

# Features
## HistoryController
AddText: Endpoint for adding text content to the user's history.
GetHistory: Endpoint for retrieving the user's text history.
DeleteHistoryEntry: Endpoint for deleting a specific entry from the user's history.
EditHistoryEntry: Endpoint for editing an existing entry in the user's history.
## UserController
### Authenticate: Endpoint for user authentication.
### RegisterUser: Endpoint for user registration.
### EditProfile: Endpoint for editing user profile information.
GetUser: Endpoint for retrieving user details.
CheckEmailExistAsync: Endpoint for checking if an email address already exists.
CreateJwt: Endpoint for creating a JSON Web Token (JWT).
CreateRefreshToken: Endpoint for creating a refresh token.
GetPrincipleFromExpiredToken: Endpoint for retrieving user information from an expired token.
Refresh: Endpoint for refreshing the access token.
SendEmail: Endpoint for sending emails.
ResetPassword: Endpoint for resetting user passwords.
# Technologies Used
ASP.NET Core: The web framework used for building RESTful APIs.
Entity Framework Core: Object-relational mapping (ORM) framework for interacting with the database.
JWT (JSON Web Tokens): Used for user authentication and authorization.
Swagger: API documentation tool for documenting and testing APIs.
Microsoft SQL Server: Database management system used for storing user data and text history.
# Getting Started
To run the project locally, follow these steps:

Clone this repository to your local machine.
Open the solution file in Visual Studio.
Update the database connection string in the appsettings.json file.
Run the database migrations to create the required tables in the database.
Build and run the application.
# API Documentation
Swagger: The project utilizes Swagger, an API documentation tool, to automatically generate interactive API documentation. This documentation provides details about the available endpoints, request parameters, response schemas, and example requests and responses. Swagger UI allows developers to explore and test the APIs directly from their web browser.
