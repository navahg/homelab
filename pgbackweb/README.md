# PGBackWeb

PGBackWeb is a web interface for PostgreSQL backups.

## Setup

Create a `.env` file from the `.env.example` file and update the values.

```bash
cp .env.example .env
```

Then, start the container.

```bash
docker compose up -d
```

Finally, you can access the pgbackweb app at `https://pgbackweb.${DOMAIN}`
