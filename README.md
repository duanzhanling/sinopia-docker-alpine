# Sinopia Alpine [![](https://images.microbadger.com/badges/image/leonardokl/sinopia-docker-alpine.svg)](https://microbadger.com/images/leonardokl/sinopia-docker-alpine "Get your own image badge on microbadger.com")

Minimal Sinopia built on Alpine Linux


## Creating a volume to storage
```
docker run -v /path/to/storage:/opt/sinopia/storage -d -p 4873:4873 leonardokl/sinopia-docker-alpine:latest
```

## Important files
- config - /opt/sinopia/storage/config.yaml
- storage - /opt/sinopia/storage
- users - /opt/sinopia/htpasswd

## Sinopia Documentation
https://github.com/rlidwka/sinopia
