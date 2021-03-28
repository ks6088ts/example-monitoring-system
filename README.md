# Prerequisites
- Docker

# Steps

1. Create `.env` file in the repository root as you want.

```bash
cp .env.sample .env
```

2. Create `shared-network` as follows

```bash
docker network create shared-network
```

3. Run services
```bash
docker-compose up -d
```

# References

- [Prometheus と Alertmanager によるモニタリングシステム入門](https://zenn.dev/ks6088ts/articles/20210328-example-monitoring-system)
