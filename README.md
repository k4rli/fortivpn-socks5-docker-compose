# Forticlient to SOCKS5

Create env `cp .env.example .env` and set VPN values

Run `docker compose --env-file=.env up -d`

Use as `SOCKS5` proxy in [Container proxy](https://addons.mozilla.org/en-US/firefox/addon/container-proxy/) or browser proxy settings.  
No username or password. `localhost:11080`
