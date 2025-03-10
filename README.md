# PIN Auth API for studying

[studying from this link](https://learn.microsoft.com/pt-br/aspnet/core/tutorials/first-web-api?view=aspnetcore-9.0&tabs=visual-studio-code)

[And this](https://dotnettutorials.net/lesson/basic-authentication-in-asp-net-core-web-api/)

* Creating a project

```dotnet
dotnet new webapi --use-controllers -o TodoApi
cd TodoApi
dotnet add package Microsoft.EntityFrameworkCore.InMemory
code -r ../TodoApi
```

* Trust the HTTPS development certificate by running the following command:

```dotnet
dotnet dev-certs https --trust
```

* Run the following command to start the application in the https profile:

```dotnet
dotnet run --launch-profile https
```
