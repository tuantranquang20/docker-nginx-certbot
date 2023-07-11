# Setup Nginx with Let’s Encrypt on docker-compose

## Installation
1. [Install Docker & Docker Compose on server](https://viblo.asia/p/docker-va-cac-kien-thuc-can-ban-BQyJKjEb4Me#_cai-dat-6).

2. Add domains and email address to init-letsencrypt.sh.

3. Run the init script: `sh init-letsencrypt.sh`.

4. Run: `docker-compose up -d`.