# Home Assistant

Home Assistant is an open-source home automation platform.

## Setup

Create a `.env` file from the `.env.example` file and update the values.

```bash
cp .env.example .env
```

Then, start the container.

```bash
docker compose up -d
```

Finally, you can access the home assistant app at `https://home.${DOMAIN}`

## Troubleshooting

1. If you are unable to access the home assistant app, try the following:
    1. Make sure the port `8123` is open on the host machine and is accessible from the docker network.
2. If you are unable to connect to HomeBridge from Apple Home, try the following:
    1. Make sure the port HASS HomeKit Bridge Port (Eg. `21064`) is open on the host machine and is accessible from the iPhone.
