# Microservices with Docker, Flask, and React

## Running

`docker-compose up -d --build`

## Testing

`docker-compose exec users python manage.py test`

## Console

`docker-compose exec users flask shell`

## Database shell

`docker-compose exec users-db psql -U postgres user_dev`

## Seed database

`docker-compose exec users python manage.py recreate_db`
