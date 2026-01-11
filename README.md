

# Multi User Todo Application using Django

![Project Image](https://raw.githubusercontent.com/Ayushsav/Todo_app_using_django/c49a051ea6dee5429ea6e2e7a05a2f0299ab1ec7/todo/todo/static/js/Screenshot%20(24).png)


# Django To-Do App 📝

A simple To-Do web application built using **Django**.  
Users can create, update, and delete tasks through a clean interface.

## Tech Stack

- Python 3.13.7  
- Django 5.2.5  
- SQLite (default database)  
- HTML, CSS, JavaScript  

---

## Project Structure

todo/ ├── manage.py ├── db.sqlite3 ├── todo/ │   ├── init.py │   ├── settings.py │   ├── urls.py │   ├── views.py │   └── wsgi.py ├── templates/ ├── static/ └── README.md

---

## Setup Instructions (Local)

### 1. Clone the Repository
```bash
git clone <https://github.com/SUBHAM-SAMANTRAY/todoappusingdjango>
cd todo


---

2. Create Virtual Environment

python -m venv venv

Activate it:

Windows

venv\Scripts\activate


---

3. Install Dependencies

pip install django

(If requirements.txt exists)

pip install -r requirements.txt


---

4. Apply Database Migrations

python manage.py migrate


---

5. Run the Development Server

python manage.py runserver

Open in browser:

http://127.0.0.1:8000/


---

Features

Add tasks

Edit tasks

Delete tasks

Mark tasks as completed

Simple and clean UI



---

Common Errors & Fixes

Error: src refspec main does not match any

Fix:

git branch -M main
git push -u origin main


---

Static files not loading

Ensure in settings.py:

STATIC_URL = '/static/'
STATICFILES_DIRS = [BASE_DIR / "static"]


---

Recommended .gitignore

venv/
__pycache__/
db.sqlite3
*.pyc


---

License

This project is created for learning and practice purposes.


---

Author

Subham Samantray

---

If you want, next I can:
- Generate `requirements.txt`
- Fix `.gitignore` properly
- Clean your repo (remove `__pycache__`, `.pyc`)
- Make a **production-ready README**

Just say it.
