# Django Development with Docker from scratch
Example of Docker configuration for Django application development.

## Working with manage.py utility
General usage:
- `docker-compose run --rm app ./manage.py [command] [params]`
Some examples:
1. Start project
- `docker-compose run --rm app django-admin startproject [project_name] .`
2. Start application
- `docker-compose run --rm app ./manage.py startapp [app_name]`
