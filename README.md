# CleanArchitectureExample
A Clean Architecture template for .NET applications.
# Clean Architecture Example in .NET

This is a Clean Architecture template for .NET applications.

## Setup

1. Clone the repository:
    ```sh
    git clone https://github.com/<your-username>/CleanArchitectureExample.git
    ```

2. Navigate into the project folder:
    ```sh
    cd CleanArchitectureExample
    ```

3. Restore the NuGet packages:
    ```sh
    dotnet restore
    ```

4. Build the solution:
    ```sh
    dotnet build
    ```

5. Run the application:
    ```sh
    dotnet run --project CleanArchitecture.WebAPI
    ```

## Project Structure

- **Domain Layer**: Contains core business logic and entities.
- **Application Layer**: Contains use cases, commands, queries, and interfaces.
- **Infrastructure Layer**: Implements repositories, data access, and external integrations.
- **Web API Layer**: Contains controllers and API endpoints.

## NuGet Packages

- **MediatR**: For CQRS pattern.
- **EF Core**: For data access.
- **Swagger**: For API documentation.

## License

This project is licensed under the MIT License.
