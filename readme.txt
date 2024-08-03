create virtual envirnomant
- python3 -m venv .venv

activate envirnomen
- source .venv/bin/activate

Deactivate envirnoment
- deactivate

create requirements.txt
- pip freeze > requirements.txt

project initialisation
- pip install django
- pip install djangorestframework
- django-admin startproject crudoperation .

start django serve
- python3 manage.py runserver
- runserver on ip python3 manage.py runserver (ip):(port)

makemigrations
- python3 manage.py makemigrations
- python3 manage.py migrate

create super user
- python3 manage.py createsuperuser 
- mail
- password
