# Open Web UI

Open Web UI is a web interface for OpenAI's API.

## Setup

Create a `.env` file from the `.env.example` file and update the values.

```bash
cp .env.example .env
```

Then, start the container.

```bash
docker compose up -d
```

Finally, you can access the open-webui app at `https://ai.${DOMAIN}`
