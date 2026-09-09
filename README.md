# 📊 SurveyBasket API

[![.NET](https://img.shields.io/badge/.NET-8.0%20%2F%209.0-512BD4?style=flat&logo=dotnet)](https://dotnet.microsoft.com/)
[![C#](https://img.shields.io/badge/C%23-12.0-239120?style=flat&logo=csharp)](https://docs.microsoft.com/en-us/dotnet/csharp/)
[![REST API](https://img.shields.io/badge/API-RESTful-009639?style=flat)](https://restfulapi.net/)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

**SurveyBasket** is a robust and scalable **RESTful Web API** built with **ASP.NET Core**, designed to handle complete survey management, poll generation, question tracking, secure user voting, and real-time result analytics.

---

## 🌟 Key Features

- 📝 **Polls & Surveys Management:** Create, update, publish, and toggle polls with customizable voting timeframes.
- ❓ **Questions & Options:** Dynamic question creation supporting multiple answer choices.
- 🗳️ **Voting System:** Secure voting mechanism ensuring single/authorized participation per user.
- 📈 **Results & Analytics:** Real-time aggregation of survey responses and statistics.
- 🔐 **Authentication & Authorization:** JWT (JSON Web Tokens) based authentication with role/permission management.
- 🛡️ **Validation & Error Handling:** Centralized exception handling with structured API responses and FluentValidation.

---

## 🏗️ Architecture & Technologies

This project adheres to modern software architecture practices (**Clean Architecture / Layered Architecture**) ensuring separation of concerns, testability, and maintainability.

- **Framework:** ASP.NET Core API
- **Language:** C#
- **Database:** SQL Server
- **ORM:** Entity Framework Core (EF Core)
- **Security:** JWT Authentication & ASP.NET Core Identity
- **Validation:** FluentValidation
- **API Documentation:** Swagger / OpenAPI

---

## 🚀 Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) (Version 8.0 or higher)
- [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) or LocalDB
- [Git](https://git-scm.com/)

### Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/ahmedsherifsamy/SurveyBasket.git](https://github.com/ahmedsherifsamy/SurveyBasket.git)
   cd SurveyBasket
