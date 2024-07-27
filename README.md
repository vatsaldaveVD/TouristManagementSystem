# Tourist Management System

## Overview

The Tourist Management System is a C#.NET Windows Forms application designed to streamline the management of tourist sites, reservations, payments, discounts, and packages. This project incorporates various design patterns to ensure a robust, maintainable, and scalable application architecture.

## Features

- **User Management**: Admin and Tourist roles with authentication.
- **Site Management**: Add, update, delete, and view tourist sites.
- **Reservation Management**: Book, view, and manage reservations. Directly associate packages with reservations.
- **Payment Management**: Handle payments and track payment status.
- **Discount Management**: Create and apply discounts.
- **Package Management**: Create and manage packages, and associate them with reservations.
- **Report Generation**: Generate and download reservation reports as CSV files.
- **Design Patterns**: Incorporates Singleton, Factory, Repository, and Observer patterns.

## Database Schema

The database schema consists of the following tables:
- **Users**: Stores user information.
- **Sites**: Stores tourist site information.
- **Payments**: Stores payment details.
- **Reservations**: Stores reservation information with associated package details.
- **Discounts**: Stores discount codes and details.
- **Packages**: Stores package information.

## Technology Stack

- **Backend**: C#.NET
- **Frontend**: Windows Forms
- **Database**: MySQL

## Getting Started

### Prerequisites

- Visual Studio 2019 or later
- .NET Framework 4.7.2 or later
- MySQL Server

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/vatsaldaveVD/TouristManagementSystem.git
    cd TouristManagementSystem
    ```

2. Set up the database:
    - Create a new database named `TouristManagementSystem`.
    - Execute the SQL script provided in `DatabaseSetup.sql` to create tables and seed initial data.

3. Configure the database connection:
    - Update the connection string in the `Database.cs` file with your MySQL server details.

4. Build and run the application:
    - Open the solution in Visual Studio.
    - Restore NuGet packages.
    - Build the solution.
    - Run the application.

## Usage

- **Admin**: Manage users, sites, packages, and discounts. View and manage all reservations and payments.
- **Tourist**: Book reservations, view own reservations, and make payments.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any enhancements or bug fixes.

## License

This project is licensed under the MIT License.
