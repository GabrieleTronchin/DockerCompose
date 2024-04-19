# Docker Compose DEV Purpose

This repository contains various Docker Compose configurations tailored for local development. It is organized into several folders:

- **config**: This directory houses an .env file providing examples of configurations.
- **docker-compose**: Within this folder, you'll find preconfigured Docker Compose files, ready for immediate use.
- **scripts**: Here, you'll discover scripts designed to streamline the deployment of the Docker Compose files.

## Spiegazione file docker compose

### MS SQL Server

The `docker-compose-sqlserver` file is responsible for configuring MS SQL Server.

### Prostgres

The `docker-compose-postgres` file is responsible for configuring Prostgres.

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


### Useful Links

[Rancher Desktop](https://rancherdesktop.io/): A free and commercial tool for Docker and/or Kubernetes in a local environment.
