# django_python

## Steps for setup

1. Creating Virtual environment - python3 -m venv venv
2. Activating Virtual environment - . venv/bin/activate
3. Install django - pip install django
4. Check Django admin - django-admin
5. Creating project - django-admin startproject files .
6. Create db - python3 manage.py runserver
7. Create super user - python manage.py createsuperuser (username: admin, email address: willcburroughs@gmail.com, password: (Hidden))
8. With super user account, now able to login
9. Created models file and imported models
10. Added drinks within settings.py as an installed app
11. Migrated models - python3 manage.py makemigrations drinks
12. Create admin file 
