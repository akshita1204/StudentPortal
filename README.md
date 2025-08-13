# StudentPortal

**Developed as part of Week 1 of my internship**

This project demonstrates a simple but functional Student Portal web application built with **ASP.NET Core MVC (.NET 8)** and **Entity Framework Core**. It implements full **CRUD (Create, Read, Update, Delete)** functionality for managing student data.

---

##  Features

- **Create**: Add new student records.
- **Read**: View all students or details of a specific student.
- **Update**: Modify existing student information.
- **Delete**: Remove student records from the system.
- Built with **ASP.NET Core MVC**, following the Model–View–Controller architecture.
- Uses **Entity Framework Core** (Code-First approach) for easy data modeling and migration.

---

##  Technologies Used

- **ASP.NET Core MVC (.NET 8)** – high-performance, cross-platform web framework :contentReference[oaicite:0]{index=0}  
- **Entity Framework Core** – modern ORM for data access and Code-First migrations :contentReference[oaicite:1]{index=1}  
- **SQL Server** (or any supported relational database)
- **Visual Studio** or **Visual Studio Code**

---

##  Project Structure

- `Models/` – Contains the `Student` model class.
- `Data/` – Holds `AppDbContext` for database configuration and migrations.
- `Controllers/` – `StudentsController` with actions for Index, Create, Edit, Details, and Delete.
- `Views/` – Razor views corresponding to each controller action.
- `Program.cs` – Configures middleware, registers `DbContext`, and sets up the MVC pipeline.

---

##  Getting Started

1. **Clone the repository**

   ```bash
   git clone https://github.com/akshita1204/StudentPortal.git
   cd StudentPortal
