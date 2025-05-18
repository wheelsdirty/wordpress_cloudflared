# Base wordpress cloudflared docker compose

This repository contains a docker-compose yaml that will get the latest wordpress, mysql database, \
and cloudflared daemon up and running on your machine. Follow the simple instructions below to get started.

## Requirements

- Docker
- Cloudflare

## Setup

1. Navigate to the directory to contain the docker compose

```bash
cd ~/PROJECT_DIR
```

2. Clone this repository

```bash
git clone git@github.com:wheelsdirty/wordpress_cloudflared.git
```

3. Add a `.env` based on `.env.example`

```bash
cp .env.example .env
```

4. Fill in the values in the `.env

5. Build the services.

```bash
docker compose build
```

6. Run the services

```bash
docker compose up
```
