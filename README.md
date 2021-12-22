# Dante proxy for aarch64
Inspired by a huge cpu utilization when using amd64 image of [wernight/docker-dante](https://github.com/wernight/docker-dante)
The idea behind `config.guess` and `config.sub` to support the **aarch64** architecture comes from [zhukovra/tgdante-arm64](https://github.com/zhukovra/tgdante-arm64)

* Build image
```bash
docker build -t cyberlight/dante-aarch64 .
```

* Push to docker registry
```
docker push cyberlight/dante-aarch64:latest
```