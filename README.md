
---

## 🖥️ Desktop Application (WPF .NET Core)

A modern **Windows desktop application** built with **WPF (.NET Core)**.
This project demonstrates the use of **Model–View–ViewModel (MVVM)** architecture, **asynchronous programming**, and **modular UI design** principles to create scalable and responsive Windows applications.

---

### 📘 Overview

This repository serves as a foundation for developing **cross-version WPF applications** using **.NET Core 3.1+** or **.NET 6+**, with a focus on maintainability, reusability, and clean architecture.

It includes:

* Modularized project structure
* MVVM framework integration
* Theme and styling management
* Command binding and data validation
* Integration-ready backend and database support

---

### 🚀 Key Features

* 🧩 **MVVM Pattern** – clear separation of UI, logic, and data.
* ⚡ **Asynchronous Operations** – smooth and responsive UI.
* 🎨 **Custom Themes & Styles** – XAML-based dynamic themes.
* 🗂️ **Modular Architecture** – easy to extend and maintain.
* 🧰 **Dependency Injection** – built-in service management.
* 💾 **SQLite / SQL Server Ready** – pluggable data source support.
* 🔧 **Configurable Settings** – stored in JSON or XML.


---

### 🏗️ Project Structure

```
Desktop-Application-WPF-Net-Core/
│
├── src/
│   ├── App.xaml / App.xaml.cs        # Application entry point
│   ├── Views/                        # UI components (Windows, Pages, UserControls)
│   ├── ViewModels/                   # ViewModel logic (commands, properties)
│   ├── Models/                       # Data models and DTOs
│   ├── Services/                     # Business logic, data access, DI
│   ├── Helpers/                      # Converters, extensions, utilities
│   └── Resources/                    # Styles, templates, icons
│
├── tests/                            # Unit test projects
│
├── DesktopApplication.sln
└── README.md
```

---

### 🧩 Technology Stack

| Component            | Technology                               |
| -------------------- | ---------------------------------------- |
| UI Framework         | WPF (.NET Core)                          |
| Language             | C#                                       |
| Architecture         | MVVM                                     |
| Dependency Injection | Microsoft.Extensions.DependencyInjection |
| Database (Optional)  | SQLite / SQL Server                      |
| Testing              | MSTest / NUnit                           |
| Build System         | MSBuild                                  |

---
