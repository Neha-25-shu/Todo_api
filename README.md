# Todo_api

# Django Rest Framework Todo App

A Simple Django Rest API Todo list generator with pagination and filtering.

# Technology Stack We have used

1. Python 3.6
2. Django REST Framework
3. sqlite3 Database
4. Google Chrome v.83.0.4103.61    
5. Google Chrome driver v.83.0.4103.61

# Linting:

make lint




# Testing:

python manage.py test

# Run the server

To run the server simply use: python manage.py runserver

# Todo

Todo are objects without logic on it, basically a todo contains just the following fields:

|Field|Description|Type| 
|----|-----|-------|
|title|title of the todo|CharField|
|completed|status of the todo|BooleanField|



# Administrator side
   * Perform CRUD operation on todo

# Project Structure:
 
```
.
├── applist
│   ├── admin.py
│   ├── apps.py
│   ├── __init__.py
│   ├── migrations
│   │   ├── 0001_initial.py
│   │   ├── __init__.py
│   │   └── __pycache__
│   │       ├── 0001_initial.cpython-37.pyc
│   │       ├── 0001_initial.cpython-39.pyc
│   │       ├── __init__.cpython-37.pyc
│   │       └── __init__.cpython-39.pyc
│   ├── models.py
│   ├── __pycache__
│   │   ├── admin.cpython-37.pyc
│   │   ├── admin.cpython-39.pyc
│   │   ├── apps.cpython-37.pyc
│   │   ├── apps.cpython-39.pyc
│   │   ├── __init__.cpython-37.pyc
│   │   ├── __init__.cpython-39.pyc
│   │   ├── models.cpython-37.pyc
│   │   ├── models.cpython-39.pyc
│   │   ├── serializers.cpython-37.pyc
│   │   ├── serializers.cpython-39.pyc
│   │   ├── urls.cpython-37.pyc
│   │   ├── urls.cpython-39.pyc
│   │   ├── views.cpython-37.pyc
│   │   └── views.cpython-39.pyc
│   ├── serializers.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
├── db.sqlite3
├── manage.py
├── requirements.txt.
└── todo
    ├── asgi.py
    ├── __init__.py
    ├── __pycache__
    │   ├── __init__.cpython-39.pyc
    │   ├── settings.cpython-39.pyc
    │   ├── urls.cpython-39.pyc
    │   └── wsgi.cpython-39.pyc
    ├── README.md
    ├── settings.py
    ├── urls.py
    └── wsgi.py


```
 
