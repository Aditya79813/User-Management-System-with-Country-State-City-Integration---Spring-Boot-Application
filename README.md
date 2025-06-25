
# User Management System with Country-State-City Integration

This is a Spring Boot-based web application designed to manage user accounts with dynamic country, state, and city selection functionality. It supports user registration, login, and password reset features.

---

## 🚀 Features

- User Registration and Login
- Password Reset Functionality
- Country-State-City Dropdown Integration
- RESTful APIs using Spring MVC
- Data Persistence with Spring Data JPA
- Maven Build Management

---

## 🛠️ Tech Stack

- **Backend**: Java 17, Spring Boot, Spring MVC, Spring Data JPA
- **Database**: H2 / MySQL (configurable)
- **Build Tool**: Maven
- **Other**: Lombok, Hibernate

---

## 📁 Project Structure

```

src/
└── main/
└── java/in/ashokit/
├── controller/         # REST controllers
├── dto/                # Data Transfer Objects
├── entity/             # JPA entities
├── repo/               # Repository interfaces
└── Application.java    # Spring Boot main class

````

---

## ⚙️ Getting Started

### Prerequisites

- Java 17+
- Maven 3.6+
- IDE (e.g., IntelliJ IDEA, Eclipse)

### Run the Application

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
````

2. Navigate to the project directory:

   ```bash
   cd 02_app-main
   ```

3. Build and run:

   ```bash
   ./mvnw spring-boot:run
   ```

4. Access the application:

   ```
   http://localhost:8080
   ```

---

## 🗂️ API Endpoints (Sample)

* `POST /register` – Register a new user
* `POST /login` – User login
* `POST /reset-password` – Reset password
* `GET /countries` – Fetch all countries
* `GET /states/{countryId}` – Fetch states by country
* `GET /cities/{stateId}` – Fetch cities by state

---

## 📌 Notes

* You may need to configure `application.properties` to connect to a real database.
* Ensure Lombok is supported in your IDE.

---

## 📜 License

This project is licensed under the MIT License.

```

Would you like me to save this `README.md` file into the extracted project folder so you can download it?
```
