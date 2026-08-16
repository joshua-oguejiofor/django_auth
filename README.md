# Django Authentication

A simple authentication system built with Django. This project demonstrates user registration, login, logout, protected routes, and authentication using Django's built-in authentication system.

## Features
- User registration
- User login
- User logout
- Password confirmation during registration
- Password hashing using Django's built-in authentication system
- Protected routes for authenticated users
- Automatic redirect for unauthenticated users
- Django authentication sessions
- Custom registration form
- Template inheritance
- Static CSS
- Environment variable management with python-dotenv
- Django class-based and function-based views

## Tech Stack
- Python
- Django
- python-dotenv
- HTML/CSS
- SQLite

## Setup
```bash
git clone <repository-url>
cd django_auth

# create a virtual enviroment
python3 -m venv .venv
source .venv/bin/activate

# install required extensions
pip install -r requirements.txt

python3 manage.py migrate
python3 manage.py runserver
```

### Open 
http://127.0.0.1:8000/ in your browser.

### Routes
- / — Home
- /register/ — Register
- /login/ — Login
- /logout/ — Logout
- /protected/ — Protected page
- /admin/ — Django admin
- Environment Variables


## Author
**Joshua Oguejiofor**