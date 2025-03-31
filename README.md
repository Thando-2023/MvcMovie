# MVC Movie Project

## Description
This project is a simple **ASP.NET Core MVC** web application, following Microsoft's tutorial on building an MVC Movie app. It includes features for adding, editing, deleting, and viewing movie entries.

## Technologies Used
- C# (.NET 9.0)
- ASP.NET Core MVC
- Entity Framework Core
- SQL Server
- Razor Pages

## Installation
### Prerequisites
- Install [.NET SDK 9.0](https://dotnet.microsoft.com/en-us/download)
- Install SQL Server or use SQLite
- Clone the repository:
   ```sh
   git clone https://github.com/Thando-2023/MvcMovie.git
   ```

### Steps
1. Navigate to the project directory:
   ```sh
   cd mvcmovie
   ```
2. Restore dependencies:
   ```sh
   dotnet restore
   ```
3. Build the project:
   ```sh
   dotnet build
   ```
4. Run the project:
   ```sh
   dotnet run
   ```
5. Open your browser and navigate to:
   ```sh
   https://localhost:5001
   ```

## Usage
- Navigate to `/Movies` to see the movie list.
- Click **Create New** to add a movie.
- Click **Edit** to modify a movie.
- Click **Delete** to remove a movie.

## Configuration
- Modify `appsettings.json` to configure database connections.
- Apply database migrations:
   ```sh
   dotnet ef migrations add InitialCreate
   dotnet ef database update
   ```

## Contributing
- Fork the repository
- Create a new branch
- Commit changes
- Open a pull request



