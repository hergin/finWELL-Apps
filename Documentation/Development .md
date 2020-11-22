


# Development:


## Tech stack:

.NET

C#

Visual Studio Community

Xamarin

NuGet

PostgreSQL

PGAdmin

Postman

  

## Packages:

Newtonsoft.Json

Microsoft.Extensions.Logging

Microsoft.Extensions.DependencyInjection

Microsoft.EntityFrameworkCore 5.0

Microsoft.AspNet.Mvc

Microsoft.AspNet.WebApi

Moq

# Replicating Development Environment

## Build the WebAPI

![](https://github.com/nmalitz/finWELL-Apps/tree/master/Documentation/Resources/development0.png)

## Testing

  

Open “Test” -> “Run All Tests” in the menu bar within Visual Studio.

The current tests only check business logic and basic mathematical formulas

![](https://github.com/nmalitz/finWELL-Apps/tree/master/Documentation/Resources/development1.png)

This is an example of the testing report from the IDE. If any tests failed they would show a red X instead of a green checkmark.

  

## File and Folder Structure

There are 3 projects that are used in the development. FinwellAPI, FinwellBackend, and FinwellApp.Tests. This separation of concerns goes hand in hand with modularity in our codebase as well as dotnet projects in general. The backend is the business logic of our projects, and it does all of the heavy lifting in terms of making a budget as well as its various categories. Our WebAPI, FinwellAPI, is generated using Swagger, and will become backend for the mobile app we will be working on in future iterations. The FinwellApp.Tests is the location for all of our unit tests throughout our project.

![](https://github.com/nmalitz/finWELL-Apps/tree/master/Documentation/Resources/development2.png)
