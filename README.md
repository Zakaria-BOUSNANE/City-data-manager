This repository provides a complete, working example of building a RESTful API using ASP.NET Core. It demonstrates fundamental concepts and best practices, allowing you to quickly grasp how to create robust APIs for your applications.

**Key Features**

* **CRUD Operations:**  Perform Create, Read, Update, and Delete actions on city information.
* **Dependency Injection:**  Learn how to manage dependencies effectively for a cleaner codebase.
* **Database Integration:**  Connect to a PostgreSQL database and interact with it using Entity Framework Core (EF Core).
* **Authentication:**  Secure your API using JWT (JSON Web Tokens) for bearer token authentication.
* **API Versioning:**  Implement API versioning to gracefully handle changes over time.
* **Documentation:**  Generate interactive Swagger/OpenAPI documentation for easy consumption of your API.
* **EF Core Migrations:**  Easily update your database schema as your API evolves.
* 
    **Prerequisites:**
   * **.NET SDK:**  Install the latest [.NET SDK](https://dotnet.microsoft.com/download).
   * **PostgreSQL:**  Install PostgreSQL and pgAdmin.
   * **Database Setup:**
      * Create a new PostgreSQL database using pgAdmin.
      * Update the `ConnectionStrings:CityInfoDBConnectionString` in your `appsettings.json` file with your database connection details.
