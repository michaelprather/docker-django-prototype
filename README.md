# docker-django-prototype
Prototpye for building a Django project using Docker

[Adopted from this tutorial](https://docs.docker.com/samples/django/): 

## To create the Django project
```shell
docker-compose run web django-admin startproject demo
```

## To start the web server:

```shell
$ docker-compose up
```

## To apply migrations

```shell
docker-compose run web python manage.py migrate
```
