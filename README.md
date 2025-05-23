# Financial Tracker Spring Boot with MySQL

A simple and robust Financial Tracking application built using Spring Boot and MySQL, designed to help users manage and monitor their expenses and income efficiently.

Check this repository for frontend setup with Angular-> https://github.com/Santhoji07/Financial-Tracker-Frontend-Angular.git 

## Features

- Add, edit, and delete expense and income entries
- Categorize transactions
- View summaries and reports
- User authentication and authorization (if implemented)
- RESTful API (if exposed)
- Intuitive, user-friendly interface

## Technologies Used

- Java 17+
- Spring Boot 3.x
- Spring Data JPA
- MySQL
- Lombok
- Maven

## Getting Started

### Prerequisites

- Java 17 or above
- Maven 3.6+
- MySQL server

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/Santhoji07/Financial-Tracker-Springboot-MySql.git
   cd Financial-Tracker-Springboot-MySql/ExpenseTracker

2. **Configure the database**

Create a MySQL database and update the src/main/resources/application.properties (or application.yml) with your DB credentials:

spring.datasource.url=jdbc:mysql://localhost:3306/your_db_name
spring.datasource.username=your_username
spring.datasource.password=your_password

3. **Build and run the application**

mvn clean install
mvn spring-boot:run

4. **Access the application**

Default: http://localhost:8080
API endpoints: see controller classes

**Project Structure**

ExpenseTracker/
├── src/
│   ├── main/
│   │   ├── java/         # Java source code
│   │   ├── resources/    # Application properties, static resources
│   ├── test/             # Unit and integration tests
├── pom.xml               # Maven project file

**Contributing**
Contributions are welcome! Please open issues or submit pull requests for any improvements or bug fixes.

Author
Santhoji07

If you have specific features or usage instructions you'd like to highlight, let me know!
