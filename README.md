# HR Management System (Java)

A simple and efficient **HR Management System** built using **Java**, **JDBC**, **Spring Boot**, **MySQL**, and **File Handling**.
This project manages employee records, attendance, salary details, and basic HR operations.

---

## 🚀 Features

* Add, update, delete, and view employee details
* Attendance management
* Salary computation
* Store and retrieve logs using **file handling**
* Database connectivity using **JDBC + MySQL**
* REST APIs built with **Spring Boot**
* Modular and layered architecture (Controller → Service → Repository)

---

## 🛠️ Tech Stack

**Backend:** Java, Spring Boot
**Database:** MySQL
**Persistence:** JDBC
**File Operations:** Java I/O
**Tools:** Maven / Gradle, IntelliJ IDEA / Eclipse

---

## 📂 Project Structure

```
HR-Management-System/
│
├── src/main/java/
│   ├── com.project.hr/
│   │   ├── controller/
│   │   ├── service/
│   │   ├── repository/
│   │   ├── model/
│   │   └── util/
│
├── src/main/resources/
│   ├── application.properties
│   └── static/data-files/
│
├── SQL/
│   └── hr_database.sql
│
├── README.md
└── pom.xml
```

---

## ⚙️ Setup Instructions

### 1. Clone the Repository

```
git clone https://github.com/ayushsh25/HR-Management-System.git
```

### 2. Configure Database (MySQL)

Create a database in MySQL:

```sql
CREATE DATABASE hr_management;
```

Import the provided SQL file:

```
hr_database.sql
```

### 3. Update `application.properties`

```
spring.datasource.url=jdbc:mysql://localhost:3306/hr_management
spring.datasource.username=YOUR_USERNAME
spring.datasource.password=YOUR_PASSWORD
spring.jpa.hibernate.ddl-auto=update
```

### 4. Run the Project

Using Maven:

```
mvn spring-boot:run
```

Or from your IDE:
▶ Run the main Spring Boot application file.

---

## 📝 File Handling (Logs)

All logs and backups are stored in:

```
src/main/resources/static/data-files/
```

Used for:

* Attendance logs
* Salary calculation logs
* Error/exception logs

---

## 📡 API Endpoints (Examples)

| Method | Endpoint           | Description           |
| ------ | ------------------ | --------------------- |
| GET    | `/employees`       | Get all employees     |
| POST   | `/employees`       | Add new employee      |
| PUT    | `/employees/{id}`  | Update employee       |
| DELETE | `/employees/{id}`  | Remove employee       |
| GET    | `/attendance/{id}` | Fetch attendance data |

---

## 🧪 Testing

You can test the APIs using:

* **Postman**
* **cURL**
* **Browser for GET requests**

---

## 🤝 Contributing

Pull requests are welcome!
Feel free to open issues for new features or bugs.

---

## 📜 License

This project is released under the **MIT License**.

---

## 👤 Author

**Aayush Shah**
Java Developer | Backend Developer
GitHub: *your-username*
