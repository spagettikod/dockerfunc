# dockerfunc
All my Dockerized stuff

## Install

```sh
cp .dockerfunc ~ && . ~/.dockerfunc
```

## Corepack

Build corepack enabled compose:
```sh
docker build --file Dockerfile-corepack --tag node:18.16.1-alpine3.18-corepack .
```