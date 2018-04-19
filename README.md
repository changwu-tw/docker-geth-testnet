# geth testnet

## Before running a geth

1. Prepare your `genesis.json`
2. Create a `keysotre` for miner

> This is a toy example, don't upload your keystore on the github.

## Build geth image

```
$ docker build -t geth .
```

## Run testnet container

```
$ docker-compose up -d
```

## View logs from geth container

```
$ docker logs -f [container_id]
```

## Attach to the container

```
$ docker exec -it [container_id] bash
```
