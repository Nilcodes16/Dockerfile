# Basic Dockerfile Project

## What it does
This project builds a simple Docker image that prints **"Hello, Captain!"** to the console and then exits.

## Dockerfile Code
```dockerfile
FROM alpine:latest
CMD ["echo", "Hello, Captain!"]
