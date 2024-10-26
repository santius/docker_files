# Docker Compose Stack

This repository contains Docker Compose files to easily deploy and manage various services, including Calibre, Grafana, InfluxDB, Librespeed, Nginx, Plex, and Portainer.

## Table of Contents

- [Overview](#overview)
- [Services](#services)
  - [Calibre](#calibre)
  - [Grafana](#grafana)
  - [InfluxDB](#influxdb)
  - [Librespeed](#librespeed)
  - [Nginx](#nginx)
  - [Plex](#plex)
  - [Portainer](#portainer)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

Each service has its own Docker Compose file, making it simple to set up specific services independently or all together by combining the configurations. Ensure Docker and Docker Compose are installed on your system before proceeding.

## Services

### Calibre
Calibre is an e-book management software that provides easy access to manage, read, and convert e-books.
- **Compose File:** `docker-compose-calibre.yaml`

### Grafana
Grafana is an open-source tool for monitoring and observability, allowing you to visualize data from InfluxDB and other sources.
- **Compose File:** `docker-compose-grafana.yaml`

### InfluxDB
InfluxDB is a time-series database optimized for fast, high-availability storage and retrieval of time-series data.
- **Compose File:** `docker-compose-influxdb.yaml`

### Librespeed
Librespeed is an open-source speed test tool that can be self-hosted, allowing you to measure internet speed on your own server.
- **Compose File:** `docker-compose-librespeed.yaml`

### Nginx
Nginx is a powerful web server and reverse proxy server, ideal for handling web requests and serving static files.
- **Compose File:** `docker-compose-nginx.yaml`

### Plex
Plex is a media server application that lets you organize and stream your media files.
- **Compose File:** `docker-compose-plex.yaml`

### Portainer
Portainer is a lightweight management UI that allows you to manage your Docker containers, images, and networks.
- **Compose File:** `docker-compose-portainer.yaml`

## Usage

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   cd your-repo-name
