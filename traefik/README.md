# Traefik

## Setup

Create a `.env` file from the `.env.example` file and update the values

```bash
cp .env.example .env
```

Then, create a new file `acme.json` in the `configs` directory and set the permissions to `600`.

```bash
touch configs/acme.json
chmod 600 configs/acme.json
```

When ready, you can start the traefik container.

```bash
docker compose up -d
```

Finally, you can access the traefik dashboard at `https://traefik.${DOMAIN}`
