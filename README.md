# Plausible Analytics

Demo Plausible Analytics Deployment. This is based on <https://github.com/plausible/hosting> with some additional configurations for clickhouse logging, traefik reverse proxy with letsencrypt https certs and geoip lookups.

# Setup

Copy `example.env` and create your own `.env` file. Set your DOMAIN and ADMIN_USER_EMAIL and all the other settings in `.env`. Follow Plausible instructions for configuring.

Run `docker network create web` first time. Then to launch enverything, run:

`docker-compose up`
