# 🦁 Zoo Management System – WPF (C#) + SQL Server

A desktop-based Zoo Management System built using Windows Presentation Foundation (WPF) with C# and Microsoft SQL Server. This application enables administrators to manage zoos and their animals through a graphical interface, supporting standard database operations such as Create, Read, Update, and Delete (CRUD).

## 📌 Features

- Manage zoo records (name, location, capacity, etc.)
- Manage animal records (species, age, assigned zoo, etc.)
- Link animals to specific zoos
- Perform **Insert**, **Select**, **Update**, and **Delete** operations
- Clean and responsive UI with WPF
- SQL Server backend with stored queries for data operations

## 🛠 Technologies Used

- **C#** – for building the desktop application logic
- **WPF (Windows Presentation Foundation)** – for creating a modern user interface
- **Microsoft SQL Server** – for data storage and management
- **ADO.NET** – for connecting to and interacting with the SQL Server database

## 🧱 Database Structure

- **Zoos Table**
  - `ZooId` (Primary Key)
  - `Name`
  - `Location`
  - `Capacity`

- **Animals Table**
  - `AnimalId` (Primary Key)
  - `Name`
  - `ZooId` (Foreign Key → Zoos)

> SQL queries (INSERT, SELECT, UPDATE, DELETE) are executed directly using ADO.NET commands.

## 🚀 Getting Started

### Prerequisites

- Visual Studio 2019 or later
- .NET Framework 4.7.2 or compatible
- Microsoft SQL Server (Express or full version)
