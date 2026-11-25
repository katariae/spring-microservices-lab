# 03 · Docker

**Status:** ⬜ not started

## What I built
_Container images for each service, a `docker-compose.yaml` that runs the whole system, and Zipkin distributed tracing._

## ⭐ My extension: hand-written multi-stage Dockerfile
_One service built with my own multi-stage Dockerfile (build stage → slim runtime stage), plus healthchecks in Compose._

## How to run
```bash
docker compose up
```

## Zipkin trace
_Add a screenshot of a trace that goes gateway → conversion → exchange._

## What I learned
See [notes/03-docker.md](../notes/03-docker.md).
