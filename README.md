# Docker Commands

```
docker build -t image_name .
docker build . --no-cache
docker run --rm image_name
docker run --rm -p port:port image_id
docker pull image_name
docker image list
docker ps
docker stop
docker-compose up
docker-compose down
docker-compose ps
docker-compose run --rm composer COMMAND
docker-compose -f docker-compose.prod.yml -f docker-compose.yml up --build
```
