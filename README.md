# Signal Proxy using Caddy

Run a [Signal TLS Proxy](https://github.com/signalapp/Signal-TLS-Proxy) using [Caddy](https://caddyserver.com/) and [`caddy-l4`](https://github.com/mholt/caddy-l4).

This minimal example can be used standalone or combined with a more complex existing Caddy setup.

## Usage

Set your domain in the environment variable `SIGNAL_PROXY_DOMAIN` in `docker-compose.yml` and run `docker compose up`
