# Todo List App

### API to Todo List using Django and React

This application is made with the intention of studying the use of Django to create a Rest API

#### Environment
Copy .env.example and put your django secret key in the .env file
```
cp .env.example .env
pipenv run keygen
```

In .env
```
DJANGO_SECRET_KEY=django-insecure-<your django secret key>
```

#### Usage
Setup the database and run the server
```
pipenv shell
pipenv install
python manage.py migrate
python manage.py runserver
```
