ToDo List Web App Using Django
A clean and simple Task Management Web Application built with Django and SQLite. Manage your daily tasks efficiently with full CRUD functionality.

Features:
Create new tasks with a title and description
View all tasks in a clean list view
Mark tasks as complete or incomplete
Edit existing tasks
Delete tasks
Lightweight SQLite database — no extra setup required

ToDo-List-WebApp-Using-Django/
│
├── base/                   # App handling core todo logic
├── todo_list/              # Django project configuration
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── db.sqlite3              # SQLite database
└── manage.py               # Django management script

Output ScreenShort:
<img width="1540" height="781" alt="image" src="https://github.com/user-attachments/assets/fb825a3b-1f7e-4aa9-ba2d-0427cf231128" />

## Features

- Add tasks
- Update tasks
- Delete tasks
- Mark tasks as completed
- User authentication

---

# Installation

## 1. Clone Repository

```bash
git clone https://github.com/your-username/ToDo-List-WebApp-Using-Django.git
```

## 2. Move Into Project Folder

```bash
cd ToDo-List-WebApp-Using-Django
```

## 3. Create Virtual Environment

```bash
python -m venv env
```

## 4. Activate Virtual Environment

### Windows

```bash
env\Scripts\activate
```

### Mac/Linux

```bash
source env/bin/activate
```

---

## 5. Install Requirements

```bash
pip install -r requirements.txt
```

---

## 6. Run Migrations

```bash
python manage.py migrate
```

---

## 7. Run Server

```bash
python manage.py runserver
```

---

# Open In Browser

```text
http://127.0.0.1:8000/
```

---

# Technologies Used

- Django
- HTML
- CSS
- SQLite

---

# Author

Sampath
