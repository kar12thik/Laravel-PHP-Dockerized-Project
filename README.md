# Laravel-PHP-Dockerized-Project

Laravel PHP project created using Docker Containers

To create our Laravel project, run docker-compose run --rm composer create-project --prefer-dist laravel/laravel:^8.0 . , in your root project's folder

Open src/.env in your editor and change the configuration lines for the database connection as follows
DB_DATABASE=homestead
DB_USERNAME=homestead
DB_PASSWORD=secret

Run the project, docker-compose up server and access it on http://localhost:8000
