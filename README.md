
# Calmô API Solution

Visual Studio solution based on WebAPI with Domain Driven Design, implemented with Calmô Framework and Swagger.

## Features
- [RESTful](https://docs.oracle.com/javaee/6/tutorial/doc/gijqy.html) Web Services
- Based on [Domain Driven Design](https://www.wikiwand.com/en/Domain-driven_design) and [MVC pattern](https://www.wikiwand.com/en/Model%E2%80%93view%E2%80%93controller)
- User [CRUD](https://www.wikiwand.com/en/Create,_read,_update_and_delete) for sample purposes;
- [Swagger](https://swagger.io/) for API documentation;
- [Calmô Framework](https://github.com/calmo-framework/calmo-net) and it's magical data access (with samples)

## Structure
There are three projects in the solution:
- API Project - the actual API holder
- Domain Project - business logic
- Repository Project - data access

## Installation
- Download the ```Calmo API Solution.zip``` file from ```/dist```
- **Move** (don't extract it) it to your Visual Studio template folder (Windows 10/VS2017: ```C:\Users\[YourUsername]\Documents\Visual Studio 2017\Templates\ProjectTemplates\Visual C#```)
- Open Visual Studio
- Select ```File > New > C# > Calmo API Solution```
- Select ```Tools > NuGet Package Manager > Package Manager Console ```
- Run ```Update-Package -reinstall```
- Done, happy coding :)
