## Your Name:

# CIDM 3312 Homework 6 - Movie Database
Create an ASP.NET Core application with an EF Core Database that allows the user to list movies and add movies to the database.

## Requirements
1. Create an ASP.NET Core application with `dotnet new webapp`.
2. Bring in EF Core support with the appropriate dotnet commands.
3. Create a Models folder for the entity class and database context.
  * Implement the database context as needed in an ASP.NET Core app
  * Implement the entity class `Movie.cs`. It should have the following properties:
  
  | Data Type     | Property Name | Data Validation |
  | ------------- | ------------- | --------------- |
  | int           | MovieID       | Maximum length = 60, Minimum Length = 3, Required |
  | string        | Title         | Hi |
