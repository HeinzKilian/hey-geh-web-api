# Hey Geh Web API

A lightweight REST API as the backend for the *Hey Geh Web App* using Django REST framework.

## Project setup

### Create and run virtual environment

While in the project base directory:
```
#### Linux ####
python3 -m venv env
source env/bin/activate

#### Windows ####
py -m venv env
env\Scripts\activate
```
The *activate* script needs to be run at the start of each new terminal session.

### Install Django and Django REST framework into the virtual environment
```
pip install django
pip install djangorestframework
```

### Set environment variables
Create the file *.env* in the project base directory and add:
```
SECRET_KEY = 'xyz123'
```
(Instead of *xyz123*, set a real and secure secret key)

### Run server locally
```
#### Linux ####
python manage.py runserver

#### Windows ####
py manage.py runserver
```
