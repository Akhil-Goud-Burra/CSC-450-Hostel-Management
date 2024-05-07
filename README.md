# CSC-450-Hostel-Management

Step 1: create database and update your details in settings.py file

step2: Install

==> pipenv install djangorestframework
==> pip install djangorestframework-xml
==> pip install djoser
==> pip install drf-spectacular
==>  python manage.py spectacular --file schema.yml
==> pip freeze > requirements.txt

Step3: 
==> create a super user ==> python manage.py createsuperuser
==> create Manager Group
==> add super user to Manager Group using django admin pannel


Step 4:
==> python manage.py migrate 
==> python manage.py makemigrations 
==> python manage.py runserver

For Documentation enter this below url:

http://127.0.0.1:8000/librarymanagement/api/fourthsprint/enduser_view/documentation/

