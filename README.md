ps-ambassador

###To Activate

    venv\Scripts\activate

###To Create a new App

    django-admin startproject app .

###To run the app

    python manage.py runserver

###To start docker

    docker-compose up

###To get into Docker 

    docker-compose exec admin_api sh

###To Create an app within Docker

    python manage.py startapp users

###To do migrate within Docker

    python manage.py migrate

###To make migrations within Docker

    python manage.py makemigrations

###To create a superuser within Docker

    python manage.py createsuperuser --email a@a.com