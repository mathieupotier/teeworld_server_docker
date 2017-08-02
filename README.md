# Teeworlds server

# Usage

## Building your own

```bash
docker build --tag=teeworlds:latest .
```

```bash
docker run --rm -p 8303:8303/udp -v $PWD/serverconfig.cfg:/usr/local/teeworlds/serverconfig.cfg teeworlds:latest
```