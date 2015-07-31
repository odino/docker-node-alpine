# node-alpine

[![](https://badge.imagelayers.io/odino/docker-node-alpine:latest.svg)](https://imagelayers.io/?images=odino/docker-node-alpine:latest 'Get your own badge on imagelayers.io')

A minimal image  (~25mb) to run NodeJS on docker through docker-alpine.

## Build

```
docker build -t node-alpine .
```

## Running

```
docker run -ti node-alpine node --version && npm --version
```
