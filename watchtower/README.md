# Watchtower

Watchtower is a tool that automatically updates your Docker containers. Currently this is configured to update every 12 hours.
And this only updates containers that have the `com.centurylinklabs.watchtower.enable=true` label.

## Setup

Create a `.env` file from the `.env.example` file and update the values.

```bash
cp .env.example .env
```

When ready, you can start the watchtower container.

```bash
docker compose up -d
```
