# Template Docker Compose Setup

This repository serves as a sample template for setting up a Docker Compose environment.

## Overview

### MS SQL Server

The `docker-compose-sqlserver` file is responsible for configuring MS SQL Server.

### Redis

The `docker-compose-redis` file handles Redis setup, including:
- [Redis](https://redis.io/docs/install/)
- Redis-monitoring

### Monitoring

The `docker-compose-monitoring` file contains configurations for:
- [Metricbeat](https://www.elastic.co/beats/metricbeat)
- [Elasticsearch](https://www.elastic.co/)
- [Kibana](https://www.elastic.co/kibana)
- [Portainer](https://www.portainer.io/)

## Other Utilities

### Self-Signed Certificate
For testing purposes, use the script `selfsigned-certs-generator.ps1` to generate self-signed certificates.

### Useful Links

[Rancher Desktop](https://rancherdesktop.io/): A free and commercial tool for Docker and/or Kubernetes in a local environment.
