# Offline Examination App

## 📘 Overview
This is a **Java-based Offline Examination Application** that uses a **MySQL database** to manage students, questions, and exam results. It allows administrators to create and manage exams, while students can take exams without needing an internet connection during the session.

---

## ⚙️ Features

- 👤 **Admin Panel**:
  - Manage student accounts
  - Create, edit, and delete exams
  - Add multiple-choice
  - View and export results

- 🧑‍🎓 **Student Panel**:
  - Take exams offline
  - Timer-enabled test interface
  - Submit and review test results

- 🗄️ **Database Integration**:
  - MySQL used to store users, questions, and exam records
  - Secure and reliable data access

---

## 🛠️ Technologies Used

- **Java** (Core + JDBC)
- **MySQL** (Database)
- **Swing / JavaFX** 
- **JDBC** for database connectivity

---

## 🚀 Getting Started

### Prerequisites

- JDK 21 or above
- MySQL Server
- MySQL Workbench 

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/offline-exam-app.git
   cd offline-exam-app

2. **Set up the databse**
   - Create the database on MySQL
   - Open the MySQL_Database folder
   - Copy the 1. Database_Creation file and paste it to the MySQL Workbech then run it
     
3. **Run the application
   - Open the Editor then open the big folder named
   - Then navigate to /PDM/src/main/java
   - Go to org.group5.connectionSQL, then open MyConnection.java to update your MySQL password and username
   - Go to org.group.general package, then open and run MainMenu.java
  
