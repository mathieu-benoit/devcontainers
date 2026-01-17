FROM dhi.io/node:22-debian13-dev

# Rebuild ldconfig cache for VS Code server compatibility
RUN apt-get update \
    && apt-get install -y gzip \
    && ldconfig