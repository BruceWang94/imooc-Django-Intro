## Basic Command of Django

- `startproject`

    Creates a Django project directory structure for the given project name in the current directory or the given destination.

- `startapp`

    Creates a Django app directory structure for the given app name in the current directory or the given destination.

- `check`

    Uses the system check framework to inspect the entire Django project for common problems.

- `runsever`

    Starts a lightweight development Web server on the local machine.

- `shell`

    Starts the Python interactive interpreter.

- `test`

    Runs tests for all installed apps.

Database reletive basic command:

- `makemigrations`

    Creates new migrations based on the changes detected to your models.

- `migrate`

    Synchronizes the database state with the current set of models and migrations.

- `dumpdata`

    Outputs to standard output all data in the database associated with the named application(s).

- `loaddata`

    Searches for and loads the contents of the named fixture into the database.

## Create a Project

`django-admin startproject <project_name>`

## Run the server

`python manage.py runserver`

## Intro to project Folder

- `settings.py`

    Project settings/configuration file.

- `urls.py`

    Project URL configuration file.

- `manage.py`

    Project management file.

## Django Application VS. Django Project

- Django Project

    A Django project is a web application using Django.

    A Django project includes a set of configurations and several Django apps.

- Django Application

    A Django app is a small library representing a discrete part of a larger project.

    Every Django app can manage its own models, views, templates, static files, and URLs etc.

## Create a App

`python manage.py startapp <app_name>`

## Intro to App Folder

- `views.py`

    the file deal with views.

- `models.py`

    the file define app models.

- `admin.py`

    the file define Admin module.

- `apps.py`

    the file save the application statement.

- `tests.py`

    the file save the test examples.

- `urls.py` (need to create by ourselves)

    the file manage the URLs.

## Django Views

## Django URLs