# Daylight

A responsive, dependency-free landing page served by Nginx in a single Docker image.

## Build and run

```sh
docker build -t daylight-web .
docker run --rm -p 8080:80 daylight-web
```

Open [http://localhost:8080](http://localhost:8080) to view the page. Stop the container with `Ctrl+C`.

The page is a static demo; update its sample branding and contact email before using it for a real product.
