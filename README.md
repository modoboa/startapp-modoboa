{% if False %}

# Django Modoboa Base Template with VueJS template

## About 

This template is used by developer 

## Features ##

By default, this project template includes:

Backend:

- Modoboa

Frontend:

- VueJS

Migrations:

- Django built-in migrations

Caching:

- python-memcached

Admin:

- Includes django-debug-toolbar for development and production (enabled for superusers)

## How to use this project template to create your modoboa module ##

- Create your working environment and virtualenv
- Install Django 1.11
- pip install Django 1.11
- $ django-admin.py startapp --template https://github.com/modoboa/startapp-modoboa/archive/master.zip --extension py,html,md,rst appname
- $ cd appname
- By default dev environment use SQLite database
- $ pip install -r dev-requirements.txt
- $ python manage.py migrate
- $ python manage.py runserver

{% endif %}
# The {{ app_name|title }} Module 

## About

Describe your project here.

## Prerequisites

- Python 3.5 recommended
- Modoboa
- pip
- virtualenv (virtualenvwrapper is recommended for use during development)

## Installation

Fill out with installation instructions for your project.

# License

Indicate your licence here

