# Synology Traefik Container

This repo contains a docker compose file that runs [Traefik](https://traefik.io/traefik) as a reverse proxy to
container-hosted applications on a Synology.

## Setup

You need to create a `.env` file. Use `example.env` as a template but replace `1.2.3.4` with the host IP address on
which to bind the traefik proxy.

You also need to create a docker network called `dmz`, e.g.:

```shell
docker network create dmz
```
