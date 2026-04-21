Gnode - Self-Hosted DevOps Platform

A production-like self-hosted infrastructure running on Linux, managing 19 Docker containers across automation, monitoring, security, and web services.

Stack
Docker & Docker Compose
Reverse Proxy (Nginx/Traefik)
Monitoring: Netdata, Uptime Kuma, GoAccess
Security: CrowdSec
Apps: Nextcloud, n8n, Vaultwarden
Features
Multi-service container architecture
Automated backups and scripts
Real-time monitoring and logging
Secure access with HTTPS and reverse proxy
Project Structure
bots/ automation services
services/ core apps and databases
monitoring/ observability tools
security/ protection services
network/ configs and proxy
Getting Started
git clone <repo>
cd gnode
docker-compose up -d
