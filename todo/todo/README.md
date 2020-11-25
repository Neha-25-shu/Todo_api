## Django Rest Framework Todo App

A Simple Django Rest API Todo list generator with pagination and filtering.

### Technology Stack

1. Python 3.6
2. Django REST Framework
3. sqlite3 Database
4. Google Chrome v.83.0.4103.61    
5. Google Chrome driver v.83.0.4103.61

### Linting:

make lint


### Todo

Todo are objects without logic on it, basically a todo contains just the following fields:


|Field|Description|Type| 
|----|-----|-------|
|title|title of the todo|CharField|
|completed|status of the todo|BooleanField|



### Administrator side
   * Perform CRUD operation on todo

### Project Structure:


```
.
├── applist
│   ├── admin.py
│   ├── apps.py
│   ├── __init__.py
│   ├── migrations : database migrations
│   ├── models.py : database models for applist app
│   ├── __pycache__
│   ├── serializers.py : serializers for the models
│   ├── tests.py : test cases for view
│   ├── urls.py : urls for applist app
│   └── views.py : These views are called by API endpoints
├── db.sqlite3
├── manage.py
├── requirements.txt : requirements needs to be install
└── todo
    ├── API.md : API documentation
    ├── asgi.py
    ├── __init__.py
    ├── __pycache__
    ├── README.md : documentation file
    ├── settings.py : settings file for the project.
    ├── urls.py : base urls for apps of the projects
    └── wsgi.py

```


## Setup 

Firstly clone the repositroy then,

Install Dependencies:
```
cd Todo
pip install -r requirements.txt
```
Make Migrations:
```
./manage.py makemigrations
./manage.py migrate
```
Start server for your REST-API:
```
./manage.py runserver
```
Testing:
```
python manage.py test
```


