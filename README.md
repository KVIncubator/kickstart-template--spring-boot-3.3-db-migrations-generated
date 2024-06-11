# Spring Boot 3.3 App Sample

JWT-based Spring Security REST API.

## Technology stack

java 17, Maven, Spring Boot, JPA, Security, Postgresql, Liquibase.

## Database configuration

Application uses a Postgres as a persistent storage. Options to get it up:

1. Use remote existing postgres. It is needed to specify the path in configs.
2. Start local postgres in docker `docker-compose -f docker-compose.dev.yml up -d`
