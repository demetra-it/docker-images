FROM postgres:18
LABEL org.opencontainers.image.source="https://github.com/demetra-it/docker-images"

# Install only the client utilities we need: pg_dump and awscli.
RUN apt update && apt install -y \
      postgresql-18-pgvector \
      && rm -rf /var/lib/apt/lists/*
