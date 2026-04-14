# Drizzle Gateway

Drizzle Gateway is an open-source self-hosted Drizzle Studio to manage your databases.

## Setup

Create a `.env` file from the `.env.example` file and update the values.

```bash
cp .env.example .env
```

Then, start the container.

```bash
docker compose up -d
```

Finally, you can access the drizzle gateway at `https://drizzle-gateway.${DOMAIN}`
