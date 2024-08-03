# Creating a Web API with ASP.NET Core and MongoDB

## Overview

This project demonstrates how to develop a web API using ASP.NET Core, integrated with MongoDB for data management. It covers setting up MongoDB, creating the web API project, defining models, configuring MongoDB connections, performing CRUD operations, customizing JSON serialization, and adding authentication support.

## Authors

- **Pratik Khandelwal**
- **Scott Addie**

## Contributors

22 contributors have helped shape this project.

## Prerequisites

Before you begin, ensure you have met the following prerequisites:

- MongoDB 6.0.5 or later
- MongoDB Shell
- Visual Studio
- Visual Studio Code
- Visual Studio for Mac
- Visual Studio 2022 with ASP.NET and web development workload

## Steps

### Configure MongoDB

1. Enable MongoDB and MongoDB Shell access from anywhere on the development machine.
2. Download and Install MongoDB Shell.
3. Download and Install MongoDB.
4. Choose a Data Storage Directory.
5. Connect to MongoDB on default port 27017.

### Create the ASP.NET Core Web API Project

1. Go to File > New > Project in Visual Studio.
2. Select the ASP.NET Core Web API project type.
3. Name the project `BookStoreApi`.
4. Select the .NET 8.0 (Long Term support) framework.

### Add an Entity Model

1. Add a Models directory to the project root.
2. Add a `Book` class to the Models directory.

### Add a Configuration Model

1. Add the following database configuration values to `appsettings.json`.

### Add a CRUD Operations Service

1. Add a Services directory to the project root.
2. Add a `BooksService` class to the Services directory.

### Add a Controller

1. Add a `BooksController` class to the Controllers directory.

### Test the Web API

1. Build and run the app.
2. Navigate to `https://localhost:<port>/api/books` to test the controller's parameterless Get action method.

### Configure JSON Serialization Options

1. Change the property names' default camel casing to match the Pascal casing of the CLR object's property names.
2. Annotate the `BookName` property with the `[JsonPropertyName]` attribute.

### Add Authentication Support to a Web API

1. Use one of the following for securing web APIs and SPAs:
   - Microsoft Entra ID
   - Azure Active Directory B2C (Azure AD B2C)
   - Duende Identity Server

## Additional Resources

- View or download sample code on GitHub.
- Learn more about creating web APIs with ASP.NET Core.
- Explore controller action return types in ASP.NET Core web API.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.
