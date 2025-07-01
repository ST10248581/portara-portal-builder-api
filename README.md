# Portara API

Portara's backend service built with ASP.NET Core 8.  
This API handles authentication, multi-tenant portal logic, client/user management, file uploads, and secure communication with the frontend apps.

---

## 🚀 Features

- Multi-tenant architecture
- Secure client + admin authentication (JWT or cookie-based)
- RESTful API for:
  - Client & Portal management
  - File/document upload
  - Messaging
- SQL Server persistence
- Integration-ready (webhooks, API tokens, etc.)

---

## 📦 Stack

- ASP.NET Core 8
- Entity Framework Core
- SQL Server
- Identity or custom auth system

---

## 🛠 Getting Started

```bash
dotnet restore
dotnet ef database update
dotnet run
