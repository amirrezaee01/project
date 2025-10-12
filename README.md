# Weblog – Django Blog Platform

A fully functional **blog platform** built with **Python and Django**. This project demonstrates backend development skills, including **user authentication, CRUD operations, and clean project structure**. Ideal for learning and practicing real-world Django applications.

## Features

- User registration, login, and logout
- Create, read, update, and delete blog posts (CRUD)
- Comment system for posts
- Admin panel for managing users, posts, and comments
- Organized project structure for clean and maintainable code
- SQLite database (default Django DB)

## Tech Stack

- Backend: Python 3.8+, Django 3.x
- Database: SQLite
- Frontend: HTML, CSS
- Version Control: Git & GitHub

## Installation

# Clone the repository
git clone https://github.com/amirrezaee01/weblog.git
cd weblog

# Create a virtual environment
python -m venv venv

# Activate the virtual environment
# On Windows
venv\Scripts\activate
# On Linux / Mac
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Apply migrations
python manage.py migrate

# Create a superuser (for admin panel access)
python manage.py createsuperuser

# Run the development server
python manage.py runserver
