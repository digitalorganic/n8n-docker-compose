# Simple n8n docker compose

Start n8n service with postgres and proxy via Traefik

## Requirements

This repo must install traefik service

You can find more information about this setup on our GitHub repository: https://github.com/digitalorganic/tffrp





## How to Use

1. Change your own settings in `db.env.example`  and rename to `db.env` for postgresql settings
2. Change your own settings in `n8n.env.example`  and rename to `n8n.env` for n8n settings
3. start service 
```sh
docker compose up -d
```
