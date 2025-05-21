# ASP.NET Core Web Application – eShop Clone

This is a modern ASP.NET Core-based web application built to demonstrate best practices in web development using clean architecture principles. The project simulates an eCommerce store and includes product catalog browsing, shopping cart functionality, and a basic admin interface.

##  Tech Stack

- ASP.NET Core 8.0
- Entity Framework Core
- Razor Pages & MVC
- SQL Server
- Blazor WebAssembly (Admin Interface)
- Docker Support
- Azure-Ready Deployment

##  Features

- Catalog Management (Products, Brands, Categories)
- Shopping Cart Functionality
- User Authentication with Identity
- Admin Dashboard (Blazor WebAssembly)
- Modular Clean Architecture
- RESTful Public API for External Integration
- Docker and Azure deployment support

##  How to Run

### Option 1: Local Development

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/eshop-clone.git
   cd eshop-clone
dotnet restore
dotnet ef database update -c catalogcontext -p ./Infrastructure/Infrastructure.csproj -s ./Web/Web.csproj
dotnet ef database update -c appidentitydbcontext -p ./Infrastructure/Infrastructure.csproj -s ./Web/Web.csproj

├── src/
│   ├── Application/
│   ├── Infrastructure/
│   ├── Web/                <-- Main ASP.NET Core App
│   └── PublicApi/          <-- Public API for Blazor/Admin



---


