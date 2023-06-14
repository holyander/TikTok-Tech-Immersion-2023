# Anderson assignment_TikTok Tech Immersion_2023

![Tests](https://github.com/TikTokTechImmersion/assignment_demo_2023/actions/workflows/test.yml/badge.svg)

This is Anderson's submission of the backend assignment of 2023 TikTok Tech Immersion from TikTok's [demo template](https://github.com/TikTokTechImmersion/assignment_demo_2023).

##  Setting up
Run the following command from same directory as `docker-compose.yml` to initialise the necessary Docker containers:
```bash
docker compose up -d
```

## Installation

Requirement:

- golang 1.18+
- docker

To install dependency tools:

```bash
make pre
```

## Run

```bash
docker-compose up -d
```

Check if it's running:

```bash
curl localhost:8080/ping
```
