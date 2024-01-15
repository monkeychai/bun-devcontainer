FROM oven/bun:alpine

RUN apk add --no-cache \
    git \
    sqlite

RUN rm -rf /home/bun/app
WORKDIR /workspace