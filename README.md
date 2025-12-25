# Home Lab

Personal home server setup for self-hosted services and learning DevOps basics.

## Services

- Nextcloud - personal cloud storage
- Navidrome - music streaming server
- Audiobookshelf - audiobooks and podcasts server
- Kavita - ebooks and manga server

Each service lives in its own directory and is deployed using Docker Compose.

## Structure

```text
home-lab/
├── nextcloud/
│   └── docker-compose.yml
├── navidrome/
│   └── docker-compose.yml
├── audiobookshelf/
│   └── docker-compose.yml
├── kavita/
│   └── docker-compose.yml


## Usage

Each service can be started independently:

```bash
docker compose up -d


Configuration files, secrets and data directories are excluded from the repository.