FROM ubuntu:20.10
SHELL ["/bin/bash", "-oeux", "pipefail", "-c"]

RUN apt-get update && \
    apt-get install -y build-essential && \
    rm -rf /var/lib/apt/lists/*

WORKDIR /workspace