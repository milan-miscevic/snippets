```bash
docker run composer:2 composer -V
docker exec -it CONTAINER_NAME bash
docker exec -it -u 0 CONTAINER_NAME bash
```

```bash
docker-php-ext-enable xdebug
```

```bash
docker stop $(docker ps -a -q)
docker rm $(docker ps -a -q)
docker network prune
docker system prune -a
docker volume prune
```
