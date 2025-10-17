# n8n-CAI-Runtimes

This repository contains a Dockerfile for building a custom n8n runtime image with CAI (Custom AI) integrations.

Docker image: kevintalbert/n8ncairuntimes:v1

Usage

Pull the pre-built image from Docker Hub:

```bash
docker pull kevintalbert/n8ncairuntimes:v1
```

Run the container (example):

```bash
docker run --rm -p 5678:5678 kevintalbert/n8ncairuntimes:v1
```

Build locally from the included `Dockerfile`:

```bash
docker build -t kevintalbert/n8ncairuntimes:v1 .
```

Notes

- The image tag `v1` identifies the release used in examples above.
- See the `Dockerfile` in this repository for the build details and any environment variables or files that should be provided at runtime.

If you want me to add more examples (docker-compose, Kubernetes manifests, or environment variable documentation), tell me which you'd like and I will add them.
