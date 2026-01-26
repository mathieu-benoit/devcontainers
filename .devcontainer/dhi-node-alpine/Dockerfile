FROM dhi.io/node:24-alpine3.23-sfw-dev

RUN apk update \
    && apk add --no-cache \
        # needed by devcontainer to start.
        musl-utils \
        gzip \
    # Rebuild ldconfig cache for VS Code server compatibility.
    && ldconfig

# Start the container as non-root user.
USER node
