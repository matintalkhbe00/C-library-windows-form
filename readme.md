# Library Management Project

This project is a C# Windows Forms application designed to manage a library's operations. It handles book registration, customer registration, loan and return of books, user credit management, and all other necessary features for a library.

## Features

- **Book Registration:** Add, edit, and delete books in the library.
- **Customer Registration:** Register and manage library users.
- **Loan Management:** Record loans and returns of books.
- **User Credit Management:** Manage and track the credit and borrowing history of users.
- **Reporting:** Generate various reports on book loans, returns, and user activities.

## Requirements

- **Programming Language:** C#
- **Platform:** .NET Framework (or .NET Core)
- **Database:** SQL Server (or any other database you prefer)

## Installation and Setup

1. **Clone the repository:**
    ```bash
    git clone https://github.com/matintalkhbe00/C-library-windows-form.git
    cd C-library-windows-form
    ```

2. **Open the project in Visual Studio:**
    - Open the `LibraryManagement.sln` file in Visual Studio.

3. **Database configuration:**
    - Enter your database connection details in the `appsettings.json` file.

4. **Run migrations:**
    ```bash
    dotnet ef database update
    ```

5. **Run the application:**
    - Run the application from Visual Studio.

## Contributing

We welcome contributions! Please create an issue first to discuss any proposed changes before submitting a pull request.

