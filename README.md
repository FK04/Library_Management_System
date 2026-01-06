# 📚 CODTECH-Task-01

- **Name:** Syed Abdul Qader Faizan Khundmiry  
- **Organization:** CODTECH IT Solutions  
- **Internship ID:** CT6WDS1928  
- **Domain:** Python Programming  
- **Duration:** September – November 2024  
- **Mentor:** Neela Santhosh Kumar  

---

## 📌 Project Overview

### Project Title: Library Management System

The **Library Management System** is a Python-based desktop application integrated with a MySQL database.  
It provides a simple and intuitive graphical interface to manage core library operations such as maintaining book records, searching inventory, and handling book issue/return processes.

This project is suitable for **small to medium-sized libraries** looking to digitize and streamline their inventory management.

---

## 🚀 Key Features
- **Add Books:** Insert new book records with details like title, author, category, and availability  
- **Search Books:** Quickly search books by title, author, or category  
- **Update Records:** Modify existing book information  
- **View Inventory:** Display all available books in a structured format  
- **Issue & Return:** Manage book borrowing and return operations  

---

## 🧠 Technologies Used
- **Programming Language:** Python  
- **GUI Framework:** Tkinter  
- **Database:** MySQL  

### Libraries
- `tkinter` – GUI development  
- `mysql.connector` – Database connectivity  

---

## ⚙️ Setup Instructions

### 1. Clone the repository
```bash
git clone <repository_url>
cd library-management-system
```

## 2. Install dependencies
```bash
pip install mysql-connector-python
```

## 3. Database setup
- Create a MySQL database named library_db
- Import sql_query.sql to create required tables
- Update database credentials (host, user, password) in the Python script

## 4. Run the application
```bash
python library_management_system.py
```

---

## 🔄 How It Works
- The application launches a Tkinter-based GUI
- Users can add, search, update, or delete book records
- A Treeview widget displays book data in a tabular format
- MySQL ensures data persistence and scalability

---

## 🔮 Future Enhancements
- User authentication and role-based access
- Advanced search and filtering options
- Borrowing history and analytics
- UI optimization for large datasets

---

## 🤝 Contribution
Contributions are welcome.
Feel free to raise issues, suggest enhancements, or submit pull requests to improve the project.
