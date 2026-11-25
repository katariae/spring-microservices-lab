# 02 · Microservices with Spring Cloud

**Status:** ⬜ not started

## What I built
| Service | Port | Role |
|---|---|---|
| limits-service | 8080 | Reads its config from the Config Server |
| spring-cloud-config-server | 8888 | Central config, backed by a Git repo |
| currency-exchange-service | 8000 | Exchange rates from a database |
| currency-conversion-service | 8100 | Calls currency-exchange through Feign |
| naming-server (Eureka) | 8761 | Service registry |
| api-gateway | 8765 | Single entry point, routing, logging filter |

_Check these ports against the course as you go and correct any that differ._

## Architecture
_Add the Mermaid diagram here as each service is added._

## ⭐ My extension: chaos demo
_Kill currency-exchange and show the Resilience4j circuit breaker returning the fallback response. Include the commands and before/after output._

## How to run
_Start order and commands._

## What I learned
See [notes/02-spring-cloud.md](../notes/02-spring-cloud.md).
