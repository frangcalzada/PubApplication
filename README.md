# Pub Application

Simple Pub Application to learn and strengthen knowledge in .NET 6

In this project we see:
1. C#
2. .NET 6
3. Entity Framework
4. SQL Server
5. JavaScript
6. Boostrap
7. Dependency injection
8. Front and back validators
9. MVC Pattern
10. Blazor

Within the repository there is a file "PubDataBase.sql" this is a script that you can use to create the necessary database structure, along with some test data.
If you use this script make sure to modify the FILENAME path for the .mdf and .ldf files

To connect the database to the project you have to configure "PubContext" with the data from your SQL Server, you can find that in appsettings.json

Inside the Controllers folder you can find an API "ApiBeer" to obtain a list of all the beers along with their brands. To test it you must run the 
project and using Postman make a GET request to the URL: https://localhost:{port}/api/ApiBeer
