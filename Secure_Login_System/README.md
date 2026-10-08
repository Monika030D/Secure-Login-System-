# Secure Login System

A beginner-friendly secure login web application built with Flask, SQLite and bcrypt.

## Features

- User registration
- Bcrypt password hashing
- Login and logout
- Session management
- Input validation
- Parameterized SQL queries to reduce SQL injection risk
- Protected dashboard

## Setup

### 1. Open terminal in this project folder

### 2. Create virtual environment

Windows:
python -m venv venv

### 3. Activate it

PowerShell:
.\venv\Scripts\Activate.ps1

Command Prompt:
venv\Scripts\activate

### 4. Install dependencies

pip install -r requirements.txt

### 5. Run

python app.py

### 6. Open browser

http://127.0.0.1:5000

## Important

For a real production deployment:
- Store SECRET_KEY in an environment variable.
- Use HTTPS.
- Add CSRF protection.
- Add rate limiting / account lockout.
- Configure secure cookie flags.
- Use a production WSGI server.
- Consider adding 2FA.
