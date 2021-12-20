Complete build from beginning: `docker-compose build --no-cache`

To build: `docker build --no-cache -t laravel-nginx .`

To run: `docker run --rm -p 80:80 laravel-nginx`

To up docker: `docker-compose up [optional --build]`

To run with specific mounting point for nginx: `docker run --rm -p 80:80 -v /Users/jakes/training/football-finder-docker/src/:/var/www/html/public laravel-nginx`

Run a composer command: `docker-compose run --rm composer create-project laravel/laravel .`
