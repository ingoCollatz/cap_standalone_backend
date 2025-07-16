# CapJS Standalone Wrapper Repo

Deploys the official CapJS backend on a Hetzner server using Docker Compose and Traefik.

## Usage

- Push to `main` to trigger GitHub Actions deployment.
- Uses GitHub Secrets:
  - `HETZNER_HOST`, `HETZNER_USER`, `HETZNER_SSH_KEY` for SSH access.
  - `ADMIN_KEY` for CapJS admin password.
- Deploys container with persistent data volume and Traefik routing.

## Setup

1. Configure your secrets in GitHub.
2. Update `docker-compose.yml` if needed.
3. Push to `main`.
