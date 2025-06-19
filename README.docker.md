# Docker Setup

## Quick Start

```bash
# Build the image
docker build -t my-js-app .

# Run the container
docker run -p 1313:1313 my-js-app
```

## Using Docker Compose

```bash
# Start services
docker-compose up

# Start in background
docker-compose up -d
```

## Environment Variables

- `HUGO_ENABLEGITINFO`: Enable Git info
- `HUGO_ENV`: Environment setting
- `HUGO_THEME`: Theme setting
- `HUGO_VERSION`: Version setting

## Ports

- 1313: Main application port