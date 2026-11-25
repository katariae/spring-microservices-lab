# 01 · REST API with Spring Boot

**Status:** ⬜ not started

## What I built
_Social-media REST API (users and posts) with Spring Boot, Spring Data JPA, H2 → MySQL, validation, OpenAPI docs, versioning, HATEOAS and Actuator._

## ⭐ My extension: pytest API test suite
_`tests/` will cover happy paths, 4xx errors and validation rules._

## Layout
```
social-media-api/   Spring Boot project (generated with Spring Initializr)
tests/              pytest + requests suite against the running API
```

## How to run
```bash
# 1. Start the API
cd social-media-api
./mvnw spring-boot:run

# 2. Run the tests (in a second terminal, while the API is running)
cd tests
python3 -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
pytest -v
```

## Endpoints
| Method | Path | Description |
|---|---|---|
| | | |

## What I learned
See [notes/01-rest-api.md](../notes/01-rest-api.md).
