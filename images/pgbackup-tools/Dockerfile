FROM ubuntu:24.04
LABEL org.opencontainers.image.source="https://github.com/demetra-it/docker-images"

# Install only the client utilities we need: pg_dump and awscli.
RUN apt update && apt install -y \
      postgresql-client-18 \
      awscli \
    && rm -rf /var/lib/apt/lists/*
