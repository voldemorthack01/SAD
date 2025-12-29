# SAD (Simple Application Demos)

SAD is a .NET 9.0 Console Application designed to demonstrate clean code architecture, library integration, and interactive CLI development. It serves as a playground for testing various .NET libraries and showcasing software engineering best practices.

## 🚀 Features

- **Interactive Menu**: A user-friendly CLI menu to navigate through different features.
- **ASCII Art Generation**: transforms text into ASCII banners using [Figgle](https://github.com/drewnoakes/figgle).
- **Data Humanization**: Manipulates and displays strings, enums, dates, times, timespans, numbers, and quantities in a user-friendly way using [Humanizer](https://github.com/Humanizer/Humanizer).
- **Structured Logging**: Implements robust logging (Console & File) using [Serilog](https://serilog.net/).

## 🛠️ Technology Stack

- **Framework**: .NET 9.0
- **Language**: C# 12/13
- **Libraries**:
  - `Figgle.Fonts`
  - `Humanizer`
  - `Serilog`
  - `Serilog.Sinks.Console`
  - `Serilog.Sinks.File`

## 📂 Project Structure

- **Configuration/**: Centralized application configuration (e.g., Logging).
- **Demos/**: Isolated modules for each feature demo.
- **Menu/**: Logic for user interaction and navigation.
- **Program.cs**: Application entry point.

## 🏁 Getting Started

### Prerequisites

- [.NET 9.0 SDK](https://dotnet.microsoft.com/download/dotnet/9.0)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/voldemorthack01/SAD.git
   ```
2. Navigate to the project directory:
   ```bash
   cd SAD
   ```

### Running the Application

Execute the following command in the terminal:

```bash
dotnet run
```

Follow the on-screen instructions to interact with the application.

## 📝 Logs

Runtime logs are generated in the `logs/` directory for debugging and auditing purposes (e.g., `logs/app_log20251229.txt`).

---
"SAD" might stand for **S**imple **A**pp **D**emo, or perhaps it's just a cheeky name. Either way, it's built with care!