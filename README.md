# Icecreamshop_django
An application comprising of the django framework to create orders, add them to a cart, checkout the orders.

## Create a virtual env first and add all the dependencies for your project
  mkvirtualenv icecream
### To enter the virtual env created previously
  workon test

## To create a django project 
django-admin startproject icecream

## To run the project {hostname can be altered in settings.xml, we can also have multiple host names}
python manage.py runserver

## To create a python application within the project
python manage.py startapp icecreamshop

## To initiate the migrations {connector between django and your database(postgres etc)
python manage.py makemigrations

## To create the db python files in your projects {copy of the objects created}
python manage.py sqlmigrate icecreamshop 0001

## Migrate the objects to the database we are connected to {db details can be mentioned in settings.xml}
python manage.py migrate
