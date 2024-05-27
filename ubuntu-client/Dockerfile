FROM ubuntu:latest
RUN apt-get update && apt-get install -y \
    curl \
    nano \
    git \
    && rm -rf /var/lib/apt/lists/*

RUN curl -sL https://deb.nodesource.com/setup_20.x | bash -
RUN apt-get install -y nodejs