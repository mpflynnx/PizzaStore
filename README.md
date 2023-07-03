# PizzaStore

Created as part of multiple learning paths:

Create a full stack application by using React and minimal API for ASP.NET Core

https://learn.microsoft.com/en-us/training/modules/build-web-api-minimal-spa/

This repo is for the back-end of the full stack application. 

For the front-end, see repo named: pizza-web

https://github.com/mpflynnx/pizza-web 

For the back-end, I learnt how to connect the front end and the back end and how you initially would run into problems with CORS. CORS is really about protecting your API from requests from domains that are not allowed. By configuring CORS properly, you can make your back-end allowlist the domain your front-end app is running on.

The bulk of this repo was created as part of learning path:

Use a database with minimal API, Entity Framework Core, and ASP.NET Core

https://learn.microsoft.com/en-us/training/modules/build-web-api-minimal-database/

In this module, I learned to add a database to a minimal API 
application with .NET 6 by using Entity Framework (EF) Core.

EF Core is an easy way to manage data in .NET applications. It's a 
lightweight, object-oriented, object-relational mapper that provides a 
high-level abstraction over the database. In this module, you used 
SQLite. You can also use other database providers like MySQL, 
PostgreSQL, and Microsoft SQL Server.

Minimal API enables you to create an API with only a few lines of code. 
It has all the major features that you're used to like dependency 
injection, talking to databases, and route management. A minimal API 
differs from a controller-based API because you explicitly specify the 
routes you need instead of relying on a convention-based approach like 
with a controller-based API.

There are many benefits to this approach:

Easier to get started: With four lines of code, I can have an API up and running quickly.

Progressive enhancement: Add features when I need them. Until then, 
your program code stays small. .NET 6 latest features: Use all the 
latest features from .NET 6 like top-level statements and records.

As part of this module, I learned how to add Swagger. I also added 
routes to create, read, update, and delete a resource.
