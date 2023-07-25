# Hello, Dear Stranger!

This is a simple application for my practice in the Django framework. 
I want to touch it.<br>
I'll write below about the key commands.

## First steps
Create a project with name 'dja'. <br>
`django-admin startproject dja`

Start the application. After this you can open your website at `127.0.0.1:8000`.<br>
`python3 manage.py runserver`

Create a new application inside the project. <br>
`django-admin startapp main`

## Admin panel
Admin panel will be able at http://127.0.0.1:8000/admin after starting a application. <br>
You should create admin user first. <br>
`python manage.py createsuperuser`
