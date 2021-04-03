# Django Guide

This doc is to show what commands I used to develop the API.
This document presumes you are running you virtual environment.

## Commands

### Initial Setup

```python
django-admin startproject DouglasAPI


cd DouglasAPI

python mangage.py migrate

# Command to start the application to stop it press C^c (C stands for control)
python manage.py runserver

cd DouglasAPI 

mkdir apps

cd apps

django-admin startapp articles
django-admin startapp auth
django-admin startapp core
django-admin startapp profiles
```

### Edit DouglasAPI/settings.py
