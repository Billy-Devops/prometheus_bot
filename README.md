Containerised of [prometheus_bot](https://github.com/inCaller/prometheus_bot)

## Example
```yaml
services:
  prometheus_bot:
    image: thebilly/prometheus_bot:latest
    container_name: prometheus_bot
    restart: unless-stopped
    volumes:
      - ./data/prometheus_bot/:/etc/telegrambot
    ports:
      - 9087:9087
```

## Changelog
###### v1.0 (2022-08-11)
Release Containerised Version