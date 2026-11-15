# Exam Seating Arrangement System 🎓

This project is a Java Spring Boot application designed to automate and manage exam seating arrangements efficiently across multiple departments and rooms. It features a responsive web interface using HTML, CSS, and JavaScript, and uses MySQL as the backend database.

# Key Features:

* Role-based login for Admin, Faculty, and Students (without Spring Security)

* Admin dashboard for managing students, rooms, departments, and seat allocations

* Faculty panel for viewing allocations, marking attendance, and printing seating charts

* Student portal to check assigned seat and room using registration number

* QR code

* Visual seat layout with seat highlighting

* Excel upload for bulk data import


# Tech Stack:
* Java, Spring Boot
* MySQL
* HTML, CSS, JavaScript
* REST API

This system ensures fair seating, easy monitoring, and effective exam room management. Ideal for institutions seeking an automated and user-friendly exam seating solution.

# Local Run

The project defaults to an in-memory H2 database for local startup so it can run without a MySQL server. To start it locally:

```bash
./mvnw spring-boot:run
```

For a MySQL-backed setup, set the DB environment variables before starting the app.
