Nextcloud auf Dockerumgebung

1. name der domäne ändern in .env und docker-compose container: web

2. bevor die docker container erstellt werden:
docker network create nextcloud_network

3. docker-composer starten
docker-compose up -d
