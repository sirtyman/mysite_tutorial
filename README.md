# mysite_tutorial

## Create a project:

```commandline
django-admin startproject mysite
```

- manage.py - command line tool
- settings.py - settings for this project
- urls.py - url mapping for this project

## Run the server:

```commandline
python manage.py runserver
```

```commandline
python manage.py runserver 127.0.0.1:8080
```

## Create an application:

```commandline
python manage.py startapp polls
```

## DB configuration:

SQLite is the default database.

```commandline
mysite/settings.py
```

In order to create database tables associated with INSTALLED_APPS in settings.py run
the following command:

```commandline
python manage.py migrate
```