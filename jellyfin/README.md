# Jellyfin

Jellyfin is a free, open source media server that puts your media in one place and streams it to smart TVs, streaming devices, mobile apps, and web browsers.

## Setup

Create a `.env` file from the `.env.example` file and update the values.

```bash
cp .env.example .env
```

Then, start the container.

```bash
docker compose up -d
```

Finally, you can access the budgetron app at `https://jellyfin.${DOMAIN}`
