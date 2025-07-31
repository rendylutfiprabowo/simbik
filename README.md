# SIMBIK – Thesis Supervision Information System

**SIMBIK** (Sistem Informasi Bimbingan Skripsi) is a web-based information system designed to facilitate and streamline the thesis supervision process between students and their academic supervisors.

This system allows both parties to manage supervision schedules, exchange files and feedback, track revision history, and maintain structured communication throughout the academic process.

---

## 🔧 Features

- 🧑‍🎓 Student and supervisor authentication
- 📝 Thesis topic and proposal submission
- 📁 File upload and revision tracking
- 💬 Supervisor comments and feedback
- 📊 Dashboard for students and supervisors
- 🕘 Supervision history and status monitoring

---

## 🛠 Tech Stack

- **Backend**: PHP (Laravel)
- **Frontend**: HTML, CSS, JavaScript  
- **Database**: MySQL  
 

---

## 🚀 Purpose

The main goal of SIMBIK is to digitize and simplify the thesis supervision workflow in academic institutions. It helps reduce administrative burdens while maintaining clear and documented interactions between students and lecturers.

---

## 📦 Installation

1. **Clone the repository**  
- git clone https://github.com/rendylutfiprabowo/simbik.git
- cd simbik

2. **Set up the environment**  
- Rename `.env.example` to `.env`
- Configure your database credentials in the `.env` file

3. **Install dependencies** (Laravel only)  
- composer install
- php artisan key:generate

4. **Import the database**  
- Create a database (e.g., `simbik`)
- Import `simbik.sql` via phpMyAdmin or the MySQL CLI

5. **Run the application**  
- Place the project in your local server root (e.g., `htdocs` or `public_html`)
- Access via browser: `http://localhost/simbik`

---
## 🔐 Dummy Login Accounts
Use the following dummy accounts to log in and explore the system:

🛠 Admin
Email: admin@gmail.com
Password: admin

👨‍🎓 Student
Email: 21208006@unima.ac.id
Password: 21208006

👨‍🏫 Supervisor (Lecturer)
Email: 0022036101@unima.ac.id
Password: 0022036101

---

## 📄 License

This project is intended for academic and educational use. Feel free to fork or contribute.

---

## 👥 Contributors

- (https://github.com/rendylutfiprabowo) – Initial developer  
- Contributions are welcome!

---

## 📬 Contact

For questions or collaborations, please contact via GitHub or email at: `rendylutfiprabowo123@gmail.com`
