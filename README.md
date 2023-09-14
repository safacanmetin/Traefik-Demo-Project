# Traefik Demo Project

This is a simple project that demonstrates how to set up Traefik as a reverse proxy and load balancer for Docker containers. It includes a frontend and a backend service.

## Prerequisites

- Docker: [Install Docker](https://docs.docker.com/get-docker/)
- Docker Compose: [Install Docker Compose](https://docs.docker.com/compose/install/)

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/safacanmetin/traefik-demo-project.git
   cd traefik-demo-project
   ```


Edit your hosts file (optional):

Add the following lines to your hosts file:

   ```bash
  127.0.0.1 frontend.localhost
  127.0.0.1 backend.localhost
   ```



Save and close the hosts file.

Start the project:
   ```bash
  docker-compose up -d
   ```

Open your web browser and visit:

  * https://frontend.localhost
  * https://backend.localhost


Configuration
The project uses Traefik as a reverse proxy with automatic HTTPS using Let's Encrypt. You can modify the Traefik configuration in the docker-compose.yml file.

    
For more: https://doc.traefik.io/traefik/
