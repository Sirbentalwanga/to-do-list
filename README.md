Blazor C# To-Do List Web Application

Table of Contents
- Introduction
- Prerequisites
- Installation
- Running the Application
- Features

## Introduction
This is a simple To-Do List application built using Blazor Server, which allows users to manage their tasks effectively. The application supports adding, editing, deleting, and searching for tasks, with validations in place to ensure data integrity.

## Prerequisites
To run this Blazor Server application, ensure you have the following installed on your Windows machine:
- Visual Studio (20.19, 2022 or later) with the ASP.NET and web development workload
- .NET Core SDK (version 3.1 or later)
- SQLite Database or any other backend database (SQLite is used in this application)

## Installation
1. Clone this repository to your local machine using:

2. Open the solution file (.sln) in Visual Studio.

3. Restore the following NuGet packages by adding them or by running the following commands:
dotnet add package Microsoft.EntityFrameworkCore.Sqlite
dotnet add package Microsoft.EntityFrameworkCore.Tools
dotnet add package Microsoft.EntityFrameworkCore.Design



## Running the Application
1. Open the Project: Unzip the folder. Open the Blazor application project in Visual Studio.
2. Set as Startup Project: Ensure the project is set as the Startup Project in Visual Studio.
3. Run the Application: Press Ctrl + F5 or click the "Run" button to start the application.
4. Access the Application: Navigate to https://localhost:5001 in your web browser.

## Features
- Add New To-Do Items: Enter new tasks and add them to the list.
- Edit To-Do Items: Edit existing tasks with a dedicated edit section.
- Delete To-Do Items: Select and delete tasks from the list.
- Search Functionality: Search tasks using any part of the title with case-insensitivity.
- Validation: Ensure titles are not empty before submission.


