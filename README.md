# Django Ledger Starter Template
### Zero Configuration Project Starter for Django Ledger

# Instructions

Clone the django starter template & CD into it
```shell
git clone https://github.com/arrobalytics/django-ledger-starter.git && cd django-ledger-starter 
```

If pipenv is not installed on your system you may install it
```shell
pip install pipenv
```

```shell
pipenv install && pipenv shell
```

Run migrations
```shell
python manage.py migrate
```

Create Django super user and follow the prompts
```shell
python manage.py createsuperuser
```

Run te server
```shell
python manage.py runserver
```

Navigate to http://127.0.0.1:8000/ledger