# SkillSquare Web API - Enterprise Backend Architecture

## About This Repository
This repository serves as a technical portfolio showcase demonstrating the backend architecture and engineering standards of **SkillSquare**, a comprehensive service booking platform. 

*Note: This repository is strictly a read-only architectural showcase designed for portfolio and evaluation purposes. It highlights our adherence to clean code principles, scalable system design, and secure API development. It is not intended for open-source cloning or distribution.*

## Live API Demo & Testing
The API is live and fully documented. You can explore and test the endpoints directly through our Swagger UI interface.

**Live API Documentation (Swagger):** (https://skillsquare-live-api-b9czenhchfhxdwbp.centralindia-01.azurewebsites.net/index.html)

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

---

## Let's Connect
Developed and engineered by **Alpha Tech Solutions**.

For business inquiries, system architecture discussions, or enterprise software solutions, let's connect:
* **Email:** [alphatechofficialpk@gmail.com](mailto:alphatechofficialpk@gmail.com)
* **LinkedIn:** [Alpha Tech Solutions](https://www.linkedin.com/company/alpha-tech-ai/)
