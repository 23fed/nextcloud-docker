# Nextcloud on Docker

Follow these steps to deploy Nextcloud in your Docker environment.

## 1. Configuration
Update your domain name and environment variables in both the `.env` file and the `docker-compose.yml` (specifically under the `web` or `app` service).

## 2. Create the Network
Before launching the containers, manually create the external network to ensure proper communication between services:

```bash
docker network create nextcloud_network
```

## Start Compose file
```bash
docker compose up -d
```

