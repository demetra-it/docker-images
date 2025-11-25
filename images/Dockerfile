FROM postgres:18

# Install only the client utilities we need: pg_dump and awscli.
RUN apt update && apt install -y \
      postgresql-18-pgvector
