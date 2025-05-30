# Matter Server

Python server to interact with Matter.

## Setup

Create a `.env` file from the `.env.example` file and update the values.

```bash
cp .env.example .env
```

Then, start the container.

```bash
docker compose up -d
```

## Troubleshooting

1. If you are unable to commission a device, try the following:
    1. Make sure the port `5580` is open on the host machine and is accessible from the matter devices.
