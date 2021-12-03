# Storage service
S3 compatible storage service using [Minio](https://min.io/)

This repo supplies the `minio` docker-compose service using docker image `minio/minio`.

# Quickstart
Run
```bash
docker-compose up
```
and navigate to [http://localhost:9001](http://localhost:9001)

The persistent data is stored to `docker/<stage>/data1`

Prometheus metrics available on grafana dashboard "storage service"
# Links
 - [Minio](https://min.io/)
 - [https://docs.min.io/docs/deploy-minio-on-docker-compose.html](https://docs.min.io/docs/deploy-minio-on-docker-compose.html)

