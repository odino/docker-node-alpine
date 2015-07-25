# node-alpine

A minimal image  (~25mb) to run NodeJS on docker through docker-alpine.

## Build

```
docker build -t node-alpine .
```

## Running

```
docker run -ti node-alpine node --version && npm --version
```
