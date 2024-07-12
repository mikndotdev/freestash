# freestash

Run an Upstash REST API compatible database on your local machine.<br>
This compose file will spin up a Redis database with an accompanying Upstash proxy.

## Usage

```bash
docker-compose up -d
```

## Configuration

The following environment variables can be used to configure the container.

| Variable | Default | Description |
|----------|---------|-------------|
| `UPSTASH_PROXY_PORT` | 8000 | The port to expose the Upstash proxy on.
| `UPSTASH_TOKEN` | upstash | The token to use for authentication.

## Credits

This project is based on the [upstash-redis-local](https://github.com/darthbenro008/upstash-redis-local) project.