# 🎓 College Management System

A robust and user-friendly **College Management System** developed using **VB.NET** (Windows Forms) and **SQL Server**. This desktop application is designed to manage various college operations like student records, courses, departments, faculty, fees, attendance, and results efficiently.



## 📌 Features

- 🧑‍🎓 **Student Management** – Add, update, delete, and view student details.
- 🏫 **Department & Course Management** – Manage courses and departments seamlessly.
- 👨‍🏫 **Faculty Management** – Add and manage faculty members.
- 💰 **Fee Management** – Track and manage student fee payments.
- 🗓️ **Attendance Management** – Record and view attendance reports.
- 📝 **Exam & Result Management** – Enter marks and generate student result reports.
- 🔒 **Authentication System** – Login system for Admin and Users with role-based access.
- 📦 **Database Integration** – All data stored securely in SQL Server database.



## 🛠️ Technologies Used

- **Frontend**: VB.NET (Windows Forms Application)
- **Backend**: SQL Server
- **Database Connectivity**: ADO.NET

---

## 🖥️ How to Run

1. Clone the repository:

   
   git clone https://github.com/Shubhamraj1909/College-Management-System
   

2. Open the solution (`.sln`) file in **Visual Studio**.

3. Configure your **SQL Server**:
   - Create a new database using the provided `.sql` file.
   - Update the **connection string** in your `App.config` or code.

4. Build and run the project.



## 🧩 Folder Structure

```
📁 CollegeManagementSystem
├── 📂 Forms           # All Windows Forms (UI)
├── 📂 Database        # .sql file to set up database schema
├── 📂 Classes         # Business logic and data access
├── CollegeMgmt.sln    # Visual Studio Solution




## 🗃️ Database

- The database includes the following tables:
  - `Students`
  - `Courses`
  - `Departments`
  - `Faculty`
  - `Fees`
  - `Attendance`
  - `Results`
  - `Users` (for login)

> SQL script is provided in the `/Database` folder.






