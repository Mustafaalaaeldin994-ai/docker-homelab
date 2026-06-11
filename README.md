# docker-homelab
Aspiring DevOps Engineer building hands-on projects in Linux, Docker, monitoring, networking, automation, and infrastructure management.
# Docker Homelab - NetBox Deployment

A personal homelab project demonstrating the deployment and management of NetBox using Docker Compose and Nginx.

## Overview

This project provides a containerized NetBox environment for IP Address Management (IPAM) and Data Center Infrastructure Management (DCIM).

## Technologies Used

- Docker
- Docker Compose
- NetBox
- Nginx
- PostgreSQL
- Redis
- Git
- GitHub

## Project Structure

```text
.
├── env/
├── docker-compose.yml
├── nginx.conf
├── README.md
└── LICENSE
```

## Features

- Containerized NetBox deployment
- Reverse proxy configuration with Nginx
- Easy service management using Docker Compose
- Infrastructure documentation and inventory management
- IP Address Management (IPAM)
- Rack and device management

## Deployment

Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/docker-homelab.git
cd docker-homelab
```

Start the services:

```bash
docker compose up -d
```

Check container status:

```bash
docker ps
```

View logs:

```bash
docker compose logs -f
```

## Learning Objectives

This project was built to gain hands-on experience with:

- Linux Administration
- Docker Containerization
- Infrastructure Documentation
- Network Management
- Git & GitHub
- Self-hosted Services

## Future Improvements

- SSL/TLS integration
- Automated backups
- Monitoring with Grafana
- Monitoring with Zabbix
- CI/CD with Jenkins
- Infrastructure as Code (Terraform)

## Author

**Mustafa Alaa Eldin**

IT Specialist

Certifications:
- CCNA
- CCNP
- MCSA
- AZ-900

GitHub: https://github.com/Mustafaalaaeldin994
