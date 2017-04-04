# k8s-docker-fluentd

Fluentd Docker image for kubernetes with elasticsearch.

[![Docker Repository on Quay.io](https://quay.io/repository/fluentd/k8s-docker-fluentd/status "Docker Repository on Quay.io")](https://quay.io/repository/rangertaha/k8s-docker-fluentd)


## Installs

* []()


## Run

```
docker run --name fluentd \
           --detach \
           -e FLUENT_ELASTICSEARCH_HOST=127.0.0.1 \
           -e FLUENT_ELASTICSEARCH_PORT=9200
           quay.io/rangertaha/k8s-docker-fluentd
```
