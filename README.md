# 🎓 College Attendance System

A simple **web-based attendance management system** designed for colleges to help teachers efficiently manage student attendance and records.

🌐 **Live Demo:** [College Attendance System](https://webdevcrrao-del.github.io/College-Attendance/)  
💻 **Source Code:** [GitHub Repository](https://github.com/adlurisowmya/attendance)

---

## 📋 Overview

This project allows **teachers** to mark attendance, **students** to view attendance records, and **admins** to manage users and data.  
It demonstrates a full-stack Java web application using **JSP, Servlets, JDBC, HTML, CSS, and JavaScript**.

---

## ✨ Features

- 👩‍🏫 Teacher/Admin login and management  
- 👨‍🎓 Student login and attendance view  
- 📅 Class and attendance session creation  
- ✅ Mark present/absent students  
- 📊 View overall attendance reports  
- 📱 Responsive frontend design  
- 🗄️ Database connectivity using JDBC  

---

## 🧰 Tech Stack

| Layer | Technology |
|-------|-------------|
| Frontend | HTML, CSS, JavaScript |
| Backend | Java Servlets, JSP |
| Database | MySQL (via JDBC) |
| Server | Apache Tomcat |
| Hosting | GitHub Pages (for demo UI) |

---

## 🚀 Getting Started

### 1️⃣ Prerequisites
Make sure you have:
- Java JDK 8 or above  
- Apache Tomcat (v9+ recommended)  
- MySQL Server  
- Eclipse IDE (or any Java EE IDE)

---

### 2️⃣ Setup Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/adlurisowmya/attendance.git
   ```
2. **Open in Eclipse**  
   - Go to **File → Import → Dynamic Web Project**  
   - Select the cloned folder

3. **Configure the Database**
   - Create a database named `attendance_db`
   - Run SQL scripts to create tables (students, attendance, users, etc.)
   - Update database connection details in your DAO/config file:
     ```java
     String url = "jdbc:mysql://localhost:3306/attendance_db";
     String user = "root";
     String password = "your_password";
     ```

4. **Deploy on Tomcat**
   - Right-click the project → **Run on Server**
   - Access in browser:
     ```
     http://localhost:8080/attendance/
     ```

---

## 🗂️ Project Structure

```
attendance/
├── src/
│   ├── dao/              # Database operations (JDBC)
│   ├── model/            # POJO classes
│   └── servlet/          # Business logic and controllers
│
├── WebContent/
│   ├── index.jsp         # Home/Login page
│   ├── dashboard.jsp     # Teacher/Student dashboard
│   ├── css/              # Stylesheets
│   └── js/               # JavaScript files
│
├── WEB-INF/
│   └── web.xml           # Servlet configuration
│
└── README.md
```

---

## 🧩 Future Enhancements

- Add **QR-code based** attendance marking  
- Implement **email/SMS notifications** for absentees  
- Provide **downloadable attendance reports (PDF/Excel)**  
- Enhance **UI/UX** for better responsiveness  
- Introduce **role-based authentication**

---

## 🧑‍💻 Author

**👩 Sowmya Adluri**  
📘 [GitHub Profile](https://github.com/adlurisowmya)

Feel free to fork this repo, raise issues, or suggest improvements!

---

## 📄 License

This project is open-source under the **MIT License**.

---

⭐ *If you found this project helpful, give it a star on GitHub!*
