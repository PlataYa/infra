# infra

## Docker login

Before composing containers, remember to run:

```sh
  docker login ghcr.io
```

And login with GitHub username and token with, at least, read:packages permission

## Docker Compose

Then, run:

```sh
  docker-compose up --build
```
