# Jake Wright Docker Tutorial Exercises

## Learn docker in 12 minutes

> video: https://www.youtube.com/watch?v=YFl2mCHdv24

Run a container with [chialab/php:8.4-apache](https://hub.docker.com/r/chialab/php)

For local development, use volume to mount the source code to the container.

```bash
cd learn-docker-in-12-minutes
docker run -p 3001:80 -v $(pwd)/src:/var/www/html my-php-app
```

then visit: http://localhost:3001

## Docker Compose in 12 Minutes

> video: https://www.youtube.com/watch?v=Qw9zlE3t8Ko

```bash
cd docker-compose-in-12-minutes
docker-compose up
```

then visit: http://localhost:3002
