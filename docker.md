```bash
docker exec -it CONTAINER_NAME bash
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
