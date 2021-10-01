# sitkmutt-static-web

## How to run with Docker

```bash
# Build Docker Image for rating service
docker build -t static-web:dev .

# Run web-static service on port 8080
docker run -d --name web-static -p 8080:80 static-web:dev
```

* Test with path `/ratings/1` and `/health`

## How to run with Docker Compose

```bash
docker-compose up -d --build
```