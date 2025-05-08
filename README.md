https://rad-queijadas-5319f0.netlify.app/

# 📝 User Registration CRUD App

A full-stack web application built using **React.js** for the frontend and **ASP.NET Core Web API** for the backend. The app enables users to register by submitting their details, which are stored using **SQLite** via **Entity Framework Core**. It features clean UI, form validation, RESTful API endpoints, and a blurred background layout.

---

## ✨ Features

- Full-stack React + .NET Core Web API
- User registration with `Full Name`, `Email`, and `Password`
- Frontend form validation using HTML5
- Backend model validation using `[Required]`, `[EmailAddress]` in C#
- RESTful endpoints (`GET`, `POST`, `PUT`, `DELETE`)
- Entity Framework Core ORM with SQLite
- Responsive form UI with a blurred background image
- CORS enabled for seamless React-to-API communication
- Swagger documentation for API endpoints (dev only)

---

## 🧱 Tech Stack

| Layer        | Technology                  |
|--------------|------------------------------|
| Frontend     | React, HTML5, CSS3, JavaScript |
| Backend      | ASP.NET Core Web API (C#)    |
| ORM & DB     | Entity Framework Core, SQLite |
| Testing      | Postman, curl                |
| Styling      | CSS (with Flexbox, blur, and responsive layout) |

---

## 🚀 Getting Started

### 🔧 Prerequisites

- [.NET SDK 6 or 8](https://dotnet.microsoft.com/en-us/download)
- [Node.js (v14+)](https://nodejs.org/)
- npm (comes with Node.js)

---

### 📦 Backend Setup

```bash
cd UserRegistrationAPI
dotnet restore
dotnet ef migrations add Init
dotnet ef database update
dotnet run
