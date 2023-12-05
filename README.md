# Django Ledger Starter Template
### Zero Configuration Project Starter for Django Ledger

# Instructions

Clone the django starter template & CD into it

```shell
git clone https://github.com/arrobalytics/django-ledger-starter.git && cd django-ledger-starter 
```

If docker and docker-compose are not installed on your system install them, for example on Debian/Ubuntu:

```shell
sudo apt install docker.io docker-compose
```

Start the services:

```shell
docker-compose up
```

Then navigate to:

- http://localhost:8000/ledger for django-ledger (login as `root` with password `root`)

- http://localhost:8090/?pgsql=postgres&username=ledger&db=ledger&ns=public (password: `ledger`) to browse the DB with [Adminer](https://www.adminer.org).

You can open a shell into the django container with:

```shell
docker-compose exec django bash
```

or even execute Django admin commands with:

```shell
docker-compose exec django python3 manage.py check
```