# Fullstack Blog Website

[![Python](https://img.shields.io/badge/python-3.8%2B-blue)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/flask-2.0+-green)](https://flask.palletsprojects.com/)
[![License: MIT](https://img.shields.io/badge/license-MIT-yellow.svg)](LICENSE)

A simple, responsive blog platform built with **Flask** backend and a frontend using **HTML, CSS, Bootstrap, and JavaScript**.

---

## 🚀 Features

- User registration and authentication  
- Create, edit, and delete blog posts  
- View all blog posts with pagination  
- Responsive design with Bootstrap  
- Secure password hashing and session management  
- Commenting system (optional)  
- Clean and easy-to-navigate UI

---

## 🛠️ Tech Stack

- **Backend:** Python, Flask, Flask-Login, Flask-WTF, Flask-SQLAlchemy  
- **Frontend:** HTML5, CSS3, Bootstrap 5, Vanilla JavaScript  
- **Database:** SQLite (default), easily switchable to PostgreSQL/MySQL  
- **Templating:** Jinja2 (Flask’s default)  

---

## 💻 Installation

1. **Clone the repository**

```bash
git clone https://github.com/zealizu/blog.git
cd blog

# Create virtual environment
python -m venv venv

# Activate virtual environment
# macOS/Linux
source venv/bin/activate

# Windows (PowerShell)
venv\Scripts\Activate.ps1

# Windows (CMD)
venv\Scripts\activate.bat

#install requirements
pip install -r requirements.txt
```
2. Create a .env file in the project root with:
SECRET_KEY=your_secret_key_here
DATABASE_URL=sqlite:///site.db
3. Run the development server
Flask run

