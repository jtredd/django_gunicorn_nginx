# Django Gunicorn Nginx
Base image for Django With PostgreSQL and Redis

```
docker-compose build --force-rm
docker-compose up -d
```

## Database

`echo 'CREATE DATABASE my_db;' |psql postgresql://postgres:@localhost:5432/postgres`

### Migrations

```
docker-compose run web python manage.py migrate
docker-compose run web python manage.py makemigrations polls
```


#### Getting Started With Django
For more information refer to th Django [Introduction](https://docs.djangoproject.com/en/2.0/intro)

