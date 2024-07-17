# BlogPost API
This repository contains the API for the BlogPosts project following this [Udemy Course by Sameer Saini](https://www.udemy.com/course/real-world-app-angular-aspnet-core-web-api-and-sql/?couponCode=THANKSLEARNER24). 
It is an ASP.NET Core REST API called by an Angular project. 
## Table of Contents
- [Technologies](#technologies)
- [Environment](#environment)
- [Executing the API](#executing-the-api)

## Technologies
The following technologies were used to create the REST API: 
- [ASP.NET Core Framework](https://dotnet.microsoft.com/en-us/apps/aspnet)
- [C#](https://learn.microsoft.com/en-us/dotnet/csharp/)
- [ASP.NET Core MVC](https://learn.microsoft.com/en-us/aspnet/core/mvc/overview?view=aspnetcore-8.0)
- [Entity Framework Core](https://learn.microsoft.com/en-us/ef/core/)
- [JSON](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/JSON)

## Environment
This application works on machines that have Windows 10+. This application was developed in a Windows environment, using Visual Studio 2022. For the best experience using this API, I recommend downloading [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) and running it on a Windows device. 
### *Note: This application was not tested on MacOS/Linux devices. This application may be incompatible with these OS's.*

To prepare your environment to execute this API:
1. [Install .NET 7 for your system](https://dotnet.microsoft.com/en-us/download/dotnet/7.0)
2. [Install Visual Studio 2022 (Optional)](https://visualstudio.microsoft.com/vs/)
3. Clone this GitHub Repository using the ___git clone___ command in the command line/terminal. (Shown Below)
```` bash
git clone https://github.com/DiegoFraR/BlogPost.API
````
If you are using Visual Studio 2022, open the project in VS 2022 and click the green run button at the top-middle of the page.
*Note: Make sure you are running on https.*

## Executing the API 
1. Ensure you have completed all the required steps in the previous [Environment](#environment) section.
2. Using the terminal/command line, navigate to the directory of this project on your machine using the cd command.
3. Once in this directory, run the following command:
```` bash
dotnet build
````
4. Now you are ready to run the API using the following command:
```` bash
dotnet run
````
5. The terminal will look something like this if successful.
6. You can open the Swagger API website located at the following URL: *https://localhost:7192/swagger*. This means you successfully launched the application. Now you must start the UI for the program located here(Coming Soon!).
