# Tech Stack
## Developer Platform: 
.NET https://dotnet.microsoft.com/
- .NET is an open source platform used for making various types of apps. Accutech/Moneytree primarily use .NET for development. So, in order to achieve a high level of compatibility between our project and their other existing projects, and in order to most effectively utilize the potential development environment we to which we will have access, various components of .NET were chosen throughout this project’s tech stack.
## Programming languages:
C# https://docs.microsoft.com/en-us/dotnet/csharp/
- C# is a programming language originally developed by Microsoft for their .NET platform. We will be using C# server-side in order to implement the REST API budgeting-engine, which will also serve as the backend to our app. 
## DBMS:
Everyone should read https://github.com/Phlank/Capstone-Resources/blob/master/Resources.md#databases
We will decide on the dbms monday morning after the client meeting.
## IDEs: 
Visual Studio Community / Visual Studio for Mac https://visualstudio.microsoft.com/
- Visual Studio is made by Microsoft, and while it can be used with a variety of languages and/or platforms, it provides built-in functionality for C# and the .NET platform in general. Using Visual Studio will enhance the development environment used by our team, which will increase our productivity.
## Frameworks:
Xamarin https://dotnet.microsoft.com/apps/xamarin
- Part of the .NET platform, Xamarin is a framework used for making cross-platform, mobile apps. The frontend of our app will be designed using Xamarin Sheets to leverage code written in C#.
## Package Manager: 
NuGet https://www.nuget.org/
- Part of the .NET platform, NuGet serves as a package manager, and its client tools allow for the ability to produce/consume packages.
## Libraries/Packages: 
Newtonsoft.Json https://www.nuget.org/packages/Newtonsoft.Json/ 
- For serializing/deserializing JSON objects into models.

Microsoft.Extensions.Logging https://www.nuget.org/packages/Microsoft.Extensions.Logging/5.0.0-rc.1.20451.14
- For injecting text into error messages by logging levels.

Microsoft.Extensions.DependencyInjection https://www.nuget.org/packages/Microsoft.Extensions.DependencyInjection/5.0.0-rc.1.20451.14
- For dependency injection.

Microsoft.EntityFrameworkCore https://www.nuget.org/packages/Microsoft.EntityFrameworkCore/5.0.0-rc.1.20451.13
- Allows C# developers to craft databases using code they write.

Microsoft.AspNet.Mvc https://www.nuget.org/packages/Microsoft.AspNet.Mvc/
- ASP.NET library for utilizing the MVC design pattern.

Microsoft.AspNet.WebApi https://www.nuget.org/packages/Microsoft.AspNet.WebApi/
- For designing a web-facing REST API.

Moq https://www.nuget.org/packages/Moq/
- “Mocking library” for unit tests.
