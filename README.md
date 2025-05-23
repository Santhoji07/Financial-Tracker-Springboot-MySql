# Financial Tracker Spring Boot with MySQL

A simple and robust Financial Tracking application built using Spring Boot and MySQL, designed to help users manage and monitor their expenses and income efficiently.

Check this repository for frontend setup with Angular-> https://github.com/Santhoji07/Financial-Tracker-Frontend-Angular.git 

## 🚀 Features

- **Expense & Income Management:** Add, edit, and delete transactions.
- **Categories:** Organize entries for better tracking.
- **Summaries & Reports:** Visualize your financial health.
- **Authentication & Authorization:** Secure access (if enabled).
- **RESTful API:** Integrate or extend (if endpoints exposed).
- **Modern Tech Stack:** Uses Java 17+, Spring Boot 3, MySQL, and Maven.

---

## 🛠️ Tech Stack

- **Backend:** Java 17+, Spring Boot 3.x, Spring Data JPA
- **Database:** MySQL
- **ORM:** JPA/Hibernate
- **Dependency Management:** Maven
- **Utilities:** Lombok

---

## 🏁 Quick Start

### 1. Clone the Repository

```bash
git clone https://github.com/Santhoji07/Financial-Tracker-Springboot-MySql.git
cd Financial-Tracker-Springboot-MySql/ExpenseTracker
```

### 2. Set Up MySQL

- Create a MySQL database (e.g., `financial_tracker`).

### 3. Configure Application Properties

Edit `src/main/resources/application.properties` (or `application.yml`):

```
spring.datasource.url=jdbc:mysql://localhost:3306/financial_tracker
spring.datasource.username=your_username
spring.datasource.password=your_password
spring.jpa.hibernate.ddl-auto=update
```

### 4. Build & Run

```bash
mvn clean install
mvn spring-boot:run
```

### 5. Access the App

- Default: [http://localhost:8080](http://localhost:8080)
- See controller classes for available REST endpoints

---

## 🗂️ Project Structure

```
Financial-Tracker-Springboot-MySql/
├── ExpenseTracker/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/            # Java source code (controllers, services, models)
│   │   │   ├── resources/       # config, static files
│   │   └── test/                # tests
│   ├── pom.xml                  # Maven config
└── .idea/                       # IDE config (can be ignored)
```

---

## 👥 Contributing

1. Fork the repo and create your branch.
2. Commit your changes.
3. Push to your fork and submit a pull request.

---

## 📄 License

MIT License

---

## 👤 Author

- [Santhoji07](https://github.com/Santhoji07)

---

If you have specific features or usage instructions you'd like to highlight, let me know!
