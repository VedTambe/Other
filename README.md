# 🎓 Student Management System (Laravel CRUD)

## 📌 Internship Task Assignment
**Company:** Cata Technology  
**Position:** Laravel Developer Intern  

---

## 📖 Project Overview

This project is a simple Student Management System developed using **Laravel (Latest Version)** and **MySQL**.  

The application performs complete CRUD (Create, Read, Update, Delete) operations with proper validation and MVC architecture.

---

## 🚀 Features

- ✅ Add New Student
- ✅ View Student List (Table Format)
- ✅ Edit Student Details
- ✅ Delete Student Record
- ✅ Form Validation
- ✅ Bootstrap UI
- ✅ MVC Structure Implementation

---

## 🛠️ Technologies Used

- Laravel (Latest Version)
- PHP
- MySQL
- Blade Templates
- Bootstrap 5
- MVC Architecture

---

## 🗂️ Project Structure (MVC)

app/
└── Models/
└── Student.php

app/
└── Http/
└── Controllers/
└── StudentController.php

resources/
└── views/
└── students/
├── index.blade.php
├── create.blade.php
└── edit.blade.php

routes/
└── web.php

database/
└── migrations/


---

## 🗄️ Database Structure

### Table: students

| Column Name     | Type        |
|---------------|------------|
| id            | BigInt (PK)|
| full_name     | String     |
| email         | String     |
| mobile_number | String     |
| course_name   | String     |
| created_at    | Timestamp  |
| updated_at    | Timestamp  |

---

## 📋 Validation Rules

- All fields are required
- Email must be valid format
- Mobile number must be numeric

---

## ⚙️ Installation Steps

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/student-management.git
cd student-management
2️⃣ Install Dependencies
composer install
3️⃣ Setup Environment File
cp .env.example .env
Update database details inside .env:

DB_DATABASE=student_db
DB_USERNAME=root
DB_PASSWORD=
4️⃣ Generate Application Key
php artisan key:generate
5️⃣ Run Migration
php artisan migrate
6️⃣ Start Server
php artisan serve
Open in browser:

http://127.0.0.1:8000/students
📸 Screenshots
Student List Page

Add Student Form

Edit Student Form

🎯 Evaluation Criteria Covered
Proper Laravel Folder Structure

Clean Code

Form Validation

Database Usage

Working CRUD Functionality

