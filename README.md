# Dockerized nginx Proxy

This compose file combines the nginx-proxy and acme-companion and provides a ready-to-use automated reverse proxy that will detect other docker containers and retrieve SSL certificates for them and forward incoming http/https requests.

Make sure to update *TZ* and *DEFAULT_EMAIL* in the `docker-compose.yml` to your needs.

For informations how to setup the other containers, visit check the docs of the [nginx-proxy](https://github.com/nginx-proxy/nginx-proxy) and the [acme-companion](https://github.com/nginx-proxy/acme-companion).
