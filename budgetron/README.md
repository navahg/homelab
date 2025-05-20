# Budgetron

Budgetron is a budgeting app that helps you manage your expenses and track your income.

## Prerequisites

- PostgreSQL
  - This requires a postgresql database server reachable from the docker network
  - Currently, this requires the a database with all the required schemas
    - TODO: Add a script to create the required schemas
- Google Sign In
  - This requires a google sign in client ID and secret
- Ollama
  - This requires an ollama server reachable from the docker network
- Blob Storage
  - This uses Vercel Blob Storage and need API key with read and write permissions
- Email Provider
  - This uses Resend and need API key with send permissions

## Setup

Create a `.env` file from the `.env.example` file and update the values.

```bash
cp .env.example .env
```

Then, build and start the container.

```bash
docker compose up -d
```

Finally, you can access the budgetron app at `https://budgetron.${DOMAIN}`
