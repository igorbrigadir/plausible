# Plausible Analytics

Demo Plausible Analytics Deployment. This is based on <https://github.com/plausible/hosting> with some additional configurations for clickhouse logging, traefik reverse proxy with letsencrypt https certs and geoip lookups.

# Setup

Copy `example.env` and create your own `.env` file. Set all the options like `DOMAIN` and `ADMIN_USER_EMAIL` and all the other settings in `.env`. Follow Plausible instructions for configuring. <https://docs.plausible.io/self-hosting/>

Run `docker network create web` first if running this for the first time. Then to launch enverything, run:

`docker-compose up`
