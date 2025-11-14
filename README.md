# ePay – Java + JDBC (My First Official College Project)

**ePay** is a lightweight payment application built using **pure Java and JDBC**, designed to simulate basic digital banking features.
This project is extremely special — it was the **first official mini-application I ever built during my college days**, right after learning Java and JDBC.
A real *throwback* to the time when writing a `Connection con = DriverManager.getConnection(...)` felt like magic. 😄

---

## 🚀 Features

* Create and manage user accounts
* Add/withdraw money
* Check balance
* Simple console-based UI
* Built using core Java concepts + raw JDBC
* No frameworks — just clean beginner-level Java

---

## 🎒 Why This Project Is Special

This project marks the moment when I first:

* Connected Java with a real database
* Wrote SQL queries inside Java
* Felt like a *real developer* during college
* Built an end-to-end working app for the first time

It’s not perfect — but it’s **pure nostalgia**.
A reminder of where the journey truly started. ❤️

---

## 📁 Project Structure

```
ePay-Using-JDBC/
 ├── src/
 │     └── com/epay        # Java classes (account, service, DB connection)
 ├── database.sql          # Table structure (if included)
 ├── README.md
 └── .gitignore
```

---

## 🛠️ Technologies Used

* Java (Core)
* JDBC
* MySQL / Any SQL database
* OOP concepts

---

## ▶️ How to Run

### 1. Configure Database

Create a database and required tables (if `database.sql` is included, import it).

### 2. Update DB Credentials in Code

Inside your DB connection class:

```java
String url = "jdbc:mysql://localhost:3306/epay";
String username = "root";
String password = "your_password";
```

### 3. Compile and Run

```
javac *.java
java Main
```

---
