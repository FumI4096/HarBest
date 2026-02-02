# HarBest 

A kiosk application for selling agricultural products.

## 🛠️ Tech Stack

- **NetBeans IDE** - Development environment
- **Java** - Core programming language
- **MySQL** - Database management system

## 📋 Prerequisites

Before running the application, ensure you have:
- Java Development Kit (JDK) 8 or higher
- NetBeans IDE
- MySQL Server
- MySQL Connector/J (JDBC driver)

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/FumI4096/HarBest.git
cd HarBest
```

### 2. Database Setup

1. Install and start MySQL Workbench
2. Create a new database for the application
3. Import the database schema (if provided in the project)
4. Update database connection settings in the source code

### 3. Open in NetBeans

1. Launch NetBeans IDE
2. Go to `File` → `Open Project`
3. Navigate to the cloned HarBest directory
4. Select and open the project

### 4. Configure Database Connection

Update the database credentials in the source code:
```java
String url = "jdbc:mysql://localhost:3306/your_database_name";
String username = "your_username";
String password = "your_password";
```

### 5. Build and Run

1. Right-click on the project in NetBeans
2. Select `Clean and Build`
3. Click `Run` to start the application

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork this repository
2. Create a feature branch: `git checkout -b feature/YourFeature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin feature/YourFeature`
5. Open a Pull Request

## 📝 License

This project is available for educational and personal use.
