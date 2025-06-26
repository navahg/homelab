# Authentik

Authentik is an open-source identity and access management (IAM) platform.

## Setup

Create a `.env` file from the `.env.example` file and update the values.

```bash
cp .env.example .env
```

Then, start the container.

```bash
docker compose up -d
```

Finally, you can access the authentik app at `https://auth.${DOMAIN}`

