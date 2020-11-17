# plausible
Demo Plausible Analytics Deployment with Traefik.

# Setup

* Copy `example.env` and create your own `.env` file.
* Set your domain in `docker-compose.yaml` 
* Set your email in `traefik/traefik.toml`

Follow Plausible instructions for configuring.

Run `docker network create web` first time.

to launch enverything:

`docker-compose up`
