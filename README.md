# docker compose mstream

## Description

- mStream is a music streaming server. With mStream you can access your music collection from anywhere. You can also sync your collection between your devices for offline access. Think of mStream as your private cloud.

## Configuration

#### Note: custom docker-compose file


```sh
environment:
    - PUID=1000
    - PGID=1000
    - USER=userName
    - PASSWORD=yourPassword
    - USE_JSON=false
    - TZ=Zone
```

- TZ example:

```sh
TZ=America/La_Paz
```

- Volumes path

```sh
- /path/music/:/music 
```

## Docker compose command

```sh
docker-compose up -d
```

## Reference

- [mstream.io](https://mstream.io/)
