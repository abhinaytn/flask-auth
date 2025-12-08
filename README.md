# Flask Authentication System

A simple user authentication system built with **Flask**, **SQLAlchemy**, and secure password hashing using `werkzeug.security`.

---

## Features

- User registration & login
- Sessions for authenticated pages
- Secure password hashing (`pbkdf2:sha256`)
- SQLite database using SQLAlchemy ORM
- Protected dashboard page
- Logout functionality

---

## Installation and Setup

# 1. Clone the repository
git clone https://github.com/abhinaytn/flask-auth.git
cd flask-auth

# 2. Create a virtual environment
python3 -m venv venv

# 3. Activate the virtual environment
# macOS / Linux
source venv/bin/activate

# Windows (PowerShell)
venv\Scripts\activate

# 4. Install dependencies
pip install -r requirements.txt

# 5. Run the application
python3 main.py
