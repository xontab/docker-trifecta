# docker-trifecta-preview

Docker container for [trifecta](https://github.com/ldaniels528/trifecta) v0.22.0rc8-0.10.1.0 Supports Kafka 0.10.1.0
Start the container with the following command:

```sh
docker build . --tag docker-trifecta-preview
docker run -d --name trifecta -p 9000:9000 -e ZK_HOST=localhost:2181 docker-trifecta-preview
```
where ZK_HOST is the url to your Zookeeper instance (e.g. localhost:2181).
