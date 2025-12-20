# Beginner's Series to .NET on Azure

Welcome to the **Beginner's Series to .NET on Azure**! This comprehensive course is designed to take you from zero to hero in deploying and managing .NET applications on Microsoft Azure. Through hands-on modules, you'll build a complete web application called "Munson's Pickles" - a pickle review platform - while learning essential Azure services and cloud development practices.

## 📚 Course Overview

This course provides a practical, step-by-step introduction to developing and deploying .NET applications on Azure. Each module builds upon the previous one, progressively adding more Azure services and capabilities to the demo application. By the end of this course, you'll have experience with:

- **ASP.NET Core Blazor** web applications
- **Azure App Service** for hosting web applications
- **Azure SQL Database** for relational data storage
- **Azure Blob Storage** for file and image storage
- **Azure Active Directory B2C** for authentication and identity
- **Managed Identities** for secure service-to-service communication
- **Azure Container Registry** and **Container Apps** for containerized deployments
- **Azure Functions** for serverless computing
- **API development** with ASP.NET Core Web APIs

## 🎯 What You'll Learn

Throughout this course, you'll gain hands-on experience with:

1. Building modern web applications with Blazor Server
2. Deploying applications to Azure App Service
3. Working with cloud databases using Entity Framework Core
4. Managing files and images with Azure Blob Storage
5. Implementing user authentication with Azure AD B2C
6. Securing applications with Managed Identities
7. Containerizing applications with Docker
8. Deploying containerized apps to Azure
9. Building serverless solutions with Azure Functions
10. Creating and consuming RESTful APIs

## 🥒 Demo Application: Munson's Pickles

The course centers around building "Munson's Pickles," a web application that allows users to:

- Browse different pickle products
- View product details and descriptions
- Submit reviews with ratings
- Upload photos with their reviews
- Authenticate to access personalized features

This real-world application serves as the perfect vehicle for learning Azure services, as each module enhances it with new cloud capabilities.

## 📋 Prerequisites

Before starting this course, you should have:

- Basic knowledge of C# and .NET
- Familiarity with web development concepts
- An Azure account (free tier is sufficient)
- Visual Studio 2022 or Visual Studio Code installed
- .NET 6.0 or .NET 7.0 SDK installed
- Git for source control

## 🗂️ Course Modules

### Module 2: Deploy and Data

**What you'll learn:**
- How to create an ASP.NET Core Blazor Server application
- Deploying a .NET web app to Azure App Service
- Setting up Azure SQL Database
- Using Entity Framework Core for data access
- Configuring connection strings in Azure
- Managing application configuration

**Key technologies:** ASP.NET Core, Blazor Server, Entity Framework Core, Azure App Service, Azure SQL Database

**Demo application features:** Basic product listing and review functionality with database persistence

---

### Module 3: Blob Storage

**What you'll learn:**
- Integrating Azure Blob Storage into your application
- Uploading and downloading files to/from Azure Storage
- Using the Azure Storage SDK for .NET
- Managing storage accounts and containers
- Implementing photo upload functionality

**Key technologies:** Azure Blob Storage, Azure Storage SDK, File uploads

**Demo application features:** Users can upload photos with their product reviews, stored securely in Azure Blob Storage

---

### Module 4: Identity

**What you'll learn:**
- Implementing authentication with Azure Active Directory B2C
- Configuring user sign-up and sign-in flows
- Protecting application routes and resources
- Managing user sessions
- Understanding OpenID Connect and OAuth 2.0

**Key technologies:** Azure AD B2C, Microsoft Identity Web, OpenID Connect, OAuth 2.0

**Demo application features:** User authentication for accessing review features

**Note:** This module includes two implementations:
- `4-identity`: Basic identity setup for web application
- `4-identity-implemented`: Complete implementation with authentication
- `4-identity-implemented-api`: API with JWT bearer authentication

---

### Module 5: Managed Identity

**What you'll learn:**
- Understanding Managed Identities in Azure
- Eliminating hardcoded credentials from your code
- Configuring service-to-service authentication
- Using Azure Identity library
- Securing connections to Azure Storage and other services

**Key technologies:** Azure Managed Identity, Azure Identity SDK, DefaultAzureCredential

**Demo application features:** Secure, passwordless connections to Azure Storage and other services using Managed Identity

---

### Module 6: Containers

**What you'll learn:**
- Containerizing .NET applications with Docker
- Creating Dockerfiles for ASP.NET Core apps
- Building and testing Docker images locally
- Pushing images to Azure Container Registry
- Deploying containers to Azure Container Apps
- Understanding container orchestration basics

**Key technologies:** Docker, Azure Container Registry, Azure Container Apps, Containerization

**Demo application features:** Both the web application and API packaged as Docker containers and deployed to Azure Container Apps

---

### Module 7: Functions

**What you'll learn:**
- Creating Azure Functions with .NET
- Understanding serverless computing concepts
- Working with Azure Queue Storage triggers
- Implementing Azure Table Storage output bindings
- Processing messages asynchronously
- Integrating Functions with existing applications

**Key technologies:** Azure Functions, Azure Queue Storage, Azure Table Storage, Serverless computing

**Demo application features:** A serverless function that processes uploaded review images, triggered by queue messages and storing metadata in Table Storage

---

## 🚀 Getting Started

1. **Clone this repository:**
   ```bash
   git clone https://github.com/codemillmatt/beginner-dotnet-on-azure.git
   cd beginner-dotnet-on-azure
   ```

2. **Choose a module to start with:**
   - Each numbered folder (2-7) contains a complete working version of the application at that stage
   - Start with Module 2 if you're following along from the beginning

3. **Open the solution:**
   - Navigate to the module folder
   - Open the `.sln` file in Visual Studio or the folder in VS Code

4. **Configure your Azure services:**
   - Each module requires specific Azure resources (documented within each module)
   - Update configuration files with your Azure connection strings and settings

5. **Run the application:**
   - Press F5 in Visual Studio or use `dotnet run` from the command line

## 📖 Additional Resources

- [Microsoft Learn - Azure Fundamentals](https://docs.microsoft.com/learn/paths/azure-fundamentals/)
- [ASP.NET Core Documentation](https://docs.microsoft.com/aspnet/core/)
- [Azure Documentation](https://docs.microsoft.com/azure/)
- [Blazor Documentation](https://docs.microsoft.com/aspnet/core/blazor/)
- [Azure SDK for .NET](https://azure.github.io/azure-sdk-for-net/)

## 📺 Video Course

This repository accompanies the video course available on Microsoft's learning platforms. Each module corresponds to video lessons that walk you through the concepts and implementation.

## 🤝 Contributing

This is a learning resource. If you find issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

Created by Matt Soucoup ([@codemillmatt](https://github.com/codemillmatt))

---

**Happy Learning! 🎓** Start your cloud development journey today and become proficient in deploying .NET applications to Azure!
