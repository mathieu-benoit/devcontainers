FROM dhi.io/debian-base:bookworm

# Rebuild ldconfig cache for VS Code server compatibility
RUN apt-get update \
    && apt-get install -y gzip \
    && ldconfig