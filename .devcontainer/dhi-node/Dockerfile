FROM dhi.io/node:24-debian13-sfw-dev

RUN apt-get update \
    && apt-get install -y \
        # gzip is needed by devcontainer to start.
        gzip \
    # Rebuild ldconfig cache for VS Code server compatibility.
    && ldconfig 

# Start the container as non-root user.
USER node

# Switch to bash shell instead of sh.
ENV SHELL=/bin/bash
