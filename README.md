# 🛡️ SQL Injection Demo

This repository demonstrates how SQL Injection attacks can be exploited in insecure web applications using a basic PHP-MySQL login system. It is intended strictly for **educational purposes** to help learners understand security flaws and how to prevent them.

---

## ⚠️ Disclaimer

This project is for **educational use only**. Do **not** use these techniques on real systems without proper authorization.

---

## 🚀 Getting Started

### 🛠️ Prerequisites

- PHP and MySQL (e.g., XAMPP, WAMP, MAMP)
- Web browser

---

### ⚙️ Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/DHIRAVIYASUNDARAM/sql-injection-demo.git
   ```

2. **Import the Database**

   - Open **phpMyAdmin** (or MySQL command line).
   - Create a new database named, for example: `sqldemo`.
   - Click **Import** and upload the `db.sql` file from this repository.

3. **Deploy the App Locally**

   - Move the `sql-injection-demo` folder into your web server’s root directory:
     - For XAMPP: `C:/xampp/htdocs/`
     - For WAMP: `C:/wamp64/www/`
   - Launch **XAMPP** or your preferred stack.
   - Start both **Apache** and **MySQL** services.

4. **Open the application in your browser**

   ```
   http://localhost/sql-injection-demo/
   ```

---

## 🧪 Demonstrating the SQL Injection

To demonstrate the vulnerability, try entering this input in the login form:

```sql
' OR '1'='1
```

This will bypass authentication and log you in without valid credentials, showcasing how SQL injection works.

---

## 🧠 Learning Outcomes

- Understand how SQL Injection compromises web apps.
- Learn the dangers of using unsanitized user input in SQL queries.
- Recognize the importance of secure coding practices like input validation and prepared statements.

---

## 🎥 Demo Video

▶️ **Watch the Screen Recording Demo of the College Club Website**

[![Watch Video](https://img.shields.io/badge/Click%20to%20Watch-Demo%20Video-blue?style=for-the-badge&logo=google-drive)](https://drive.google.com/file/d/1riCW5RdVJGa6UnU25Lhpl5TJjX3EnYoc/view?usp=sharing)

---
