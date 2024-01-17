# Neo4J on Fly.io

This fly.toml file will configure neo4j on fly.io for you using expected ports.

It also persists the data to a 3G disk

## First Time Deploy

```bash
fly launch --copy-config
```

## Deploy Changes

```bash
fly deploy
```
