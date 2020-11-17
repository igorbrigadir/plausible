# Plausible Analytics

Demo Plausible Analytics Deployment. This is based on <https://github.com/plausible/hosting> with some additional configurations for clickhouse logging, traefik reverse proxy with letsencrypt https certs and geoip lookups.

# Setup

You will need a server with a domain or subdomain set up and accessible from the internet. You can run this locally just to see if you use `127.0.0.1.nip.io` but https obviously won't work. You also need Docker and docker-compose set up.

# Set Environment Variables:

Copy `example.env` and create your own `.env` file. Set all the options like `DOMAIN` and `ADMIN_USER_EMAIL` and all the other settings in `.env`. Follow Plausible instructions for configuring. <https://docs.plausible.io/self-hosting/>

Run `docker network create web` first if running this for the first time.

Launch everything: 

`docker-compose up`
