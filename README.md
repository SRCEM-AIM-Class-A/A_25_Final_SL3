# 🧩 Django + Flask Multi-App Project

This repository contains two separate web applications built with **Django** and **Flask**, bundled into a single project folder. This setup is ideal for demonstrating integration, containerization, or learning both frameworks side by side.

---

## 📁 Project Structure

project-root/ │ ├── flask_app/ │ ├── app.py │ ├── templates/ │ └── static/ │ ├── django_app/ │ ├── manage.py │ ├── django_app/ # main Django project folder │ └── inventory/ # Django app (e.g., inventory system) │ ├── .gitignore └── README.md

yaml
Copy
Edit

---

## 🚀 Quick Start

### 🧪 Requirements

- Python 3.7+
- `pip` or `pipenv`
- Virtual environment (recommended)

---

### 🔹 Flask App Setup

cd flask_app
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install Flask

python app.py
Open in browser: http://localhost:5000

🔹 Django App Setup
bash
Copy
Edit
cd django_app
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install django

python manage.py migrate
python manage.py runserver
Open in browser: http://localhost:8000

🖥️ Features
✅ Flask App
Simple user input form (Name + Age)

Form validation

Styled with custom CSS

Greet user after submission

✅ Django App
Inventory listing page

Form to add new items

Server-side form validation using Django Forms

Fully styled with a colorful dashboard look

🌐 URLs
App	URL	Description

Flask	/	Homepage with link to form

Flask	/greet	Form to enter name and age

Django	/inventory/	List + add inventory items
