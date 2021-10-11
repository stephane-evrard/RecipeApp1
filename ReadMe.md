## Recipe App
- Clone the app
-create a virtual environment
-run pip freeze > requirements.text
-username: admin 
-email: admin@gmail.com 
-password: School 1

-to fill database : pip install django-seed
-run   python manage.py seed core --number=250
that will you to fill random data, about the number you can change more that 250.

then run python manage.py runserver

you can logout and create an other user an start using the application 