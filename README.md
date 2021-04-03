# Django Example

This project will produce a back-end django JSON API that is based off the repo found here:

<https://github.com/gothinkster/django-realworld-example-app>

## Reasoning behind project

There are a couple of reasons behind this project:

1. To continue my development in the backend this project is specifically with django.

2. To be a reference guide for people who struggle with setup and background information.

## Project Features

- Authentication: Handle registration and login look to replace Django default authentication with token-based using JSON Web tokens
- Profiles: Add user profile that will be automatically created on acount registration.
- Articles: This can be what people can post, read, favorite and comment on.

## Installation

First install a version of python would recommend 3.x as 2 is now depricated.
We will be doing work in a virtual environment if you use Python 3.4+ venv is baked into Python.

```python
# To use virtualenv:
python -m venv env
# You can rename env to whatever you want
```

Any other previous verion have to install it first.

```python
# To install virtualenv:
sudo pip install virtualenv
# To use virtualenv 
virtualenv env
```

Virtual Environment Activation:

Linux and MacOS venv activation:
source env/bin/activate

Windows venv activation
env\Scripts\activate.bat

Now that we are inside a venv can install django:

```python
pip install Django
```

You can then check installation with the following command:

```python
python3 -m django --version
```

Install Django REST framework

```python
pip install djangorestframework
```

Install django-extensions

```python
pip install django-extensions
```

Install django-cors-headers

```python
pip install django-cors-headers 
```

## Usage

## Commands

## Links

GitHub Link: <https://github.com/gothinkster/django-realworld-example-app>
Python Install: <https://www.python.org/downloads/>
Django Install: <https://docs.djangoproject.com/en/3.1/intro/install/>
Django API Reference: <https://docs.djangoproject.com/en/3.1/ref/>
Django Topics: <https://docs.djangoproject.com/en/3.1/topics/>
Django REST framework: <https://www.django-rest-framework.org/>
Django-extensions: <https://django-extensions.readthedocs.io/en/latest/>
Django-cors-Headers: <https://pypi.org/project/django-cors-headers/>