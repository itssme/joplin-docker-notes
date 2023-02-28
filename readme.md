# Deploy Joplin using docker-compose

This repository is a combination of:
+ https://github.com/tomdess/docker-haproxy-certbot
+ https://hub.docker.com/r/joplin/server

It should automatically get a certificate from letsencrypt and deploy joplin using docker-compose.

## Start

```bash
docker-compose up --build haproxy nginx joplin db  
```

Goto: your_domain_name:8080 and view the Joplin Web UI.
