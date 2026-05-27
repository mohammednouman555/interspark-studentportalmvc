# Student Portal MVC Application

## Objective

This project is developed using ASP.NET Core MVC with ASP.NET Identity authentication.  
The application demonstrates user registration, login, logout, authentication, authorization, and protected pages using Entity Framework Core with SQLite database.

---

# Features

- User Registration
- User Login
- User Logout
- ASP.NET Identity Authentication
- Authorization for Protected Pages
- Dashboard Access after Login
- SQLite Database Integration
- Bootstrap User Interface
- Entity Framework Core Migrations

---

# Technologies Used

- ASP.NET Core MVC
- C#
- ASP.NET Identity
- Entity Framework Core
- SQLite
- Bootstrap
- Visual Studio Code
- Git & GitHub

---

# Project Structure

StudentPortalMVC

├── Controllers  
│   ├── AccountController.cs  
│   └── HomeController.cs  

├── Data  
│   └── ApplicationDbContext.cs  

├── Models  
│   ├── LoginViewModel.cs  
│   ├── RegisterViewModel.cs  
│   └── ErrorViewModel.cs  

├── Views  
│   ├── Account  
│   ├── Home  
│   └── Shared  

├── Migrations  

├── wwwroot  

├── Program.cs  

├── appsettings.json  

└── StudentPortalMVC.csproj  

---

# Authentication Features

## Registration

Users can register using:
- Email
- Password

After successful registration, users are redirected to the dashboard.

---

## Login

Registered users can login securely using:
- Email
- Password

---

## Logout

Authenticated users can logout securely.

---

## Protected Dashboard

The Dashboard page is protected using authorization.

Only logged-in users can access:
- Dashboard page

---

# Database Used

SQLite database is used for storing:
- User accounts
- Authentication data
- Identity tables

Database File:
StudentPortal.db

---

# ASP.NET Identity Tables

The following tables are automatically generated:

- AspNetUsers
- AspNetRoles
- AspNetUserClaims
- AspNetUserLogins
- AspNetUserRoles
- AspNetUserTokens
- AspNetRoleClaims

---

# Entity Framework Core Commands

## Create Migration

```bash
dotnet ef migrations add InitialIdentity