# django-rest-app

Django Rest API with JSON web token(JWT) authentication.

## Installation

First, clone the repo:
```bash
git clone https://github.com/amahmood561
```

## Usage

```bash
cd django-rest-app
```

Create a virtual environment
https://github.com/amahmood561/django-auth-jwt/tree/master
```bash
python3 -m venv venv
```

Activate the virtual environment

```bash
source venv/bin/activate
```
Install all the packages from requirements.txt

```bash
pip3 install requirements.txt
```

Migrate

```bash
python3 manage.py migrate
```

Start the app
```bash
python3 manage.py runserver
```


API's
/signup <-post you can view page from chrome
http://127.0.0.1:8000/api/signup

/signin <- post
body:
{
 "email":"test@gmail.com",
 "password":"Spring34!"
}

http://127.0.0.1:8000/api/signin

get profile <- GET use jwt from sign in
http://127.0.0.1:8000/api/profile
