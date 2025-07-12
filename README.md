# Django Admin Playground

An experimental project to explore extensions to the Django admin interface, including a keyboard-activated command palette.

## 🔧 Features

- Ctrl+K overlay
- Keyboard shortcuts
- Django admin integration

## 🚀 Goal

This project is part of the preparation for Google Summer of Code 2026, focusing on a proposed command palette for Django Admin.

## 🛠️ Quick start

```bash
git clone https://github.com/pippotadde/django-admin-playground.git
cd django-admin-playground
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
