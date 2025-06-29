# IT Support Ticket Tracker System

A simple web-based IT support ticket system built with **Flask**, **MySQL**, **HTML/CSS**, and **GitHub**.

---

## 🚀 Features

### 👨‍💻 User Side
- 📝 Submit a support ticket with issue details
- 👀 View ticket status (Open, In Progress, Resolved)
- 📧 Receive email confirmation after ticket submission

### 🛠️ Admin Side
- 🔐 Admin login
- 📋 View all submitted tickets
- 🔄 Update ticket status

---

## 🧱 Tech Stack

| Technology | Usage             |
|------------|-------------------|
| Flask      | Backend (Python)  |
| MySQL      | Database          |
| HTML/CSS   | Frontend UI       |
| GitHub     | Version control   |
| Flask-Mail | Email handling    |

---

## 📁 Project Structure

ticket-tracker/
│
├── app.py                     # Main Flask application
├── config.py                  # Configuration for database and email
├── templates/                 # HTML templates for the frontend
│   ├── index.html             # User ticket submission page
│   ├── ticket_status.html     # User ticket status page
│   ├── admin_login.html       # Admin login page
│   ├── admin_dashboard.html   # Admin dashboard to view & update tickets
├── static/                    # Static files like CSS
│   └── style.css              # Stylesheet for the application
├── db.sql                     # SQL script to set up database tables
├── requirements.txt           # Python dependencies
└── README.md                  # Project documentation

