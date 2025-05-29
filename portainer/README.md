# Portainer

Portainer is a container management platform.

## Setup

Create a `.env` file from the `.env.example` file and update the values.

```bash
cp .env.example .env
```

Then, start the container.

```bash
docker compose up -d
```

Finally, you can access the portainer app at `https://portainer.${DOMAIN}`
