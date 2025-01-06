# Slim 4 API

Simple API using Slim v4 MySQL and optionnaly S3 Storage

## Run

- Create `.env` from `.env.exemple`
- Update environement variable
- run `php -S localhost:<PORT> -t ./public`

## run dockerfile

- make sure you are in the immo-api-php directory
- run docker compose up -d
- then run docker compose exec -it <container id> -c "composer install"

# database

- import schema.sql in your database
