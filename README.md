<<<<<<< HEAD
# SkillSquare Backend API 🚀

This is the official backend API for **SkillSquare**, a platform designed to connect users with local skilled professionals. It is built using modern .NET technologies and follows a robust repository pattern architecture.

## 🌐 Live API
**Swagger UI:** [View Live API Documentation](http://skill-square-api.runasp.net/index.html)

## 🛠️ Tech Stack
* **Framework:** ASP.NET Core 8/9 Web API
* **Language:** C#
* **Database:** Azure SQL Database & Entity Framework Core
* **Authentication:** ASP.NET Core Identity & JWT (JSON Web Tokens)
* **Real-time Communication:** SignalR (WebSockets)
* **Cloud Hosting:** Microsoft Azure App Service

## 🏗️ Architecture & Features
* **N-Tier Architecture:** Separation of concerns using Data Access Layer (DAL) and Controllers.
* **Repository Pattern:** Clean abstraction of database operations.
* **Role-Based Authorization:** Distinct access levels for Admins, Providers, and standard Users.
* **Real-time Notifications:** Instant alerts using SignalR Hubs.


## 🧪 Demo Test Credentials
To help reviewers and developers test the API, the following demo accounts are available:
### 👤 Customer
- **Email:** `test@gmail.com`
- **Password:** `Test@123`
### 🛠️ Provider
- **Email:** `provider33@gmail.com`
- **Password:** `Provider@123`
### 🛡️ Admin
- **Email:** `admin@skillsquare.com`
- **Password:** `Admin@123`

## 🔐 Authentication (How to test)
This API uses Bearer JWT for security. To test endpoints in Swagger:
1. Go to the `/api/Auth/login` endpoint.
2. Enter your credentials to receive a JWT Token.
3. Click the green **Authorize** button at the top of the Swagger page.
4. Type `Bearer ` followed by a space, and paste your token.
=======
# SkillSquare Web API - Enterprise Backend Architecture

## About This Repository
This repository serves as a technical portfolio showcase demonstrating the backend architecture and engineering standards of **SkillSquare**, a comprehensive service booking platform. 

*Note: This repository is strictly a read-only architectural showcase designed for portfolio and evaluation purposes. It highlights our adherence to clean code principles, scalable system design, and secure API development. It is not intended for open-source cloning or distribution.*

## Live API Demo & Testing
The API is live and fully documented. You can explore and test the endpoints directly through our Swagger UI interface.

**Live API Documentation (Swagger):** [Click Here](https://skillsquare-live-api-b9czenhchfhxdwbp.centralindia-01.azurewebsites.net/index.html)

### Test Credentials
To evaluate the role-based access control (RBAC) and secure endpoints, generate a JWT token via the authentication routes using the following demo credentials:

| Account Role | Email Address | Password |
| :--- | :--- | :--- |
| **Customer Portal** | `test@gmail.com` | `Test@123` |
| **Provider Portal** | `provider22@gmail.com` | `Provider@123` |

## Architectural Overview
The system is built to enterprise standards, prioritizing performance, security, and maintainability.

* **Design Pattern:** N-Tier (Multi-tier) Architecture ensuring a strict separation of concerns between Data Access, Business Logic, and API layers.
* **Security & Authentication:** Implementation of robust JWT (JSON Web Tokens) paired with ASP.NET Identity to manage complex role-based routing (Admin, Provider, Customer).
* **Data Management:** Entity Framework Core with code-first migrations, integrated into a fully normalized SQL Server database environment.

## Technical Stack
* **Core Framework:** ASP.NET Core Web API (.NET 9)
* **Programming Language:** C#
* **Database Engine:** Microsoft SQL Server
* **Cloud Infrastructure:** Microsoft Azure App Services
* **Testing & Documentation:** Swagger (OpenAPI)

