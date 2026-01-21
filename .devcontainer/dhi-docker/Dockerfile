FROM dhi.io/debian-base:trixie

# Rebuild ldconfig cache for VS Code server compatibility
RUN apt-get update \
    && apt-get install -y gzip \
    && ldconfig