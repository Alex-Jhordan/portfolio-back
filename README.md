# Portfolio backend (Headless WordPress + SQLite)

A lightweight headless WordPress backend pre-configured with SQLite support. Designed to serve structured content via WPGraphQL to a frontend framework like Astro.

## Features

- **Headless WordPress**: Serves content via GraphQL API.
- **SQLite Engine**: Zero-database setup, native file storage.
- **Dockerized Setup**: Fast local execution and seamless cloud deployment.

## Local development

1. Run the local environment using Docker Compose:
   ```bash
   docker compose up -d
   ```

2. Access the WordPress installation wizard at:
   `http://localhost:8080`

## Deployment

This repository is optimized for **Render** via Docker web service deployment:
1. Connect this GitHub repository to Render.
2. Select **Web Service** with the **Docker** runtime.
3. Enable **Auto-Deploy on commit**.