# Sazzler Service Registry

## Overview
Spring Cloud Eureka server for service discovery. All microservices register here for dynamic discovery.

## Features
- Eureka dashboard
- Service registration and health checks
- Optional authentication for dashboard

## Setup
1. Java 21+
2. Gradle
3. Configure authentication in `application.yaml` (optional)

## Build & Run
```bash
./gradlew build
./gradlew bootRun
```

## Configuration
- Port: Default 8761
- Authentication: Set username/password in `application.yaml` if needed

## Docker
- Build: `docker build -t sazzler-service-registry .`
- Run: `docker run -p 8761:8761 sazzler-service-registry`

## Troubleshooting
- Ensure port 8761 is open
- Check logs for registration errors
- Validate dashboard access

