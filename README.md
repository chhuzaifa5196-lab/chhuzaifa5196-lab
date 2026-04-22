# 📦 Inventory Management System

A console-based Inventory Management System built with C# (.NET 10).
Manage products through a clean, interactive terminal interface.

---

## 👤 Author
- **Name:** Ch. Muhammad Huzaifa
- **Roll No:** 232201036
- **Course:** Visual Programming Lab
- **Institution:** KICSIT

---

## 🛠️ Technologies Used
- C# (.NET 10)
- Docker
- Git & GitHub

- Project Structure

- InventoryManagement/
├── Models/
│   └── Product.cs
├── Services/
│   └── InventoryService.cs
├── UI/
│   ├── ConsoleHelper.cs
│   └── MenuHandler.cs
├── Program.cs
├── Dockerfile
└── README.md


---

## ✨ Features
- ✅ View All Products
- ✅ Add New Product
- ✅ Update Product
- ✅ Delete Product
- ✅ Search Products
- ✅ Restock Product
- ✅ Low Stock Report
- ✅ Inventory Summary
- ✅ Filter by Category

---

## 🚀 How to Run

### Option 1 - Run Locally
Make sure you have .NET 10 SDK installed.
```bash
dotnet run
```

### Option 2 - Run with Docker
Make sure Docker Desktop is installed.
```bash
docker build -t inventory-app .
docker run -it inventory-app
```

---

## 🖥️ Application Menu

╔══════════════════════════════════════════════╗
║  INVENTORY MANAGEMENT SYSTEM                 ║
╚══════════════════════════════════════════════╝

View All Products
Add New Product
Update Product
Delete Product
Search Products
Restock Product
Low Stock Report
Inventory Summary
Filter by Category
Exit

---

## 🏗️ Architecture
| Layer | File | Purpose |
|---|---|---|
| Model | Product.cs | Data structure |
| Service | InventoryService.cs | Business logic |
| UI | ConsoleHelper.cs | Display utilities |
| UI | MenuHandler.cs | Menu interaction |
| Entry | Program.cs | App entry point |

---

## 🐳 Docker
Multi-stage build using:
- Build stage: mcr.microsoft.com/dotnet/sdk:10.0
- Runtime stage: mcr.microsoft.com/dotnet/runtime:10.0

---

## 📄 License
This project is for educational purposes only.

---

## 📁 Project Structure
