# NB1 Stats - Hungarian Football Statistics Portal

This project is a sports statistical information portal where users can view clubs in the Hungarian Football Championship (NB1). The application allows users to browse detailed player data (such as position, market value, and jersey number) and view statistical charts.

## 🚀 Features

* **Home Page:** Provides an introduction to the NB1 Analysis Center and its services.
* **Database Listing:** Displays a comprehensive list of football players, joining data from the players, clubs, and positions tables.
* **Interactive Charts:** Features a dynamic bar chart that visualizes the number of players registered to each club.
* **CRUD Operations:** Includes a complete interface to Create, Read, Update, and Delete football clubs in the database.
* **Contact Form:** Allows visitors to send messages with server-side validation, saving them directly to the database.
* **Message Viewer:** A protected page where authenticated users can view submitted contact messages in reverse chronological order.
* **REST API:** Provides standard JSON endpoints (`GET`, `POST`, `DELETE` at `/api/klubok`) for external communication.
* **Admin Dashboard:** A secured area accessible only to administrators, listing all registered users in the system.

## 🛠️ Technologies Used

* **Backend:** Java Spring Boot with Maven project management.
* **Database:** MySQL database managed via JPA (Java Persistence API) and Hibernate ORM.
* **Frontend:** Thymeleaf template engine for dynamic HTML generation.
* **Design/UI:** Free "Editorial" responsive HTML5/CSS3 template by HTML5 UP.
* **Security:** Spring Security for user authentication and role-based authorization (Admin, User).
* **Data Visualization:** Chart.js JavaScript library.

## ⚙️ Setup and Installation

1. Ensure you have **Java** and a local database server (like **XAMPP** for MySQL) installed on your machine.
2. Clone the repository to your local machine.
3. Start your MySQL database and create a new schema for the application.
4. Update the `src/main/resources/application.properties` file with your local database connection details (URL, username, and password).
5. Run the application using your IDE or via the Maven wrapper. The application will be available at `http://localhost:8080` (or the port you configured).

## 🔐 Admin Credentials

To access the protected Admin Dashboard and message viewer, you can log in using the following default credentials:
* **Email:** Szaboviktor@gmail.com
* **Password:** Asd12345
