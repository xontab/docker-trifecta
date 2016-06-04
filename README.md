# docker-trifecta

Start the container with the following command:

```sh
docker run -d --rm --name trifecta -p 9000:9000 -e ZK_HOST=localhost:2181 janschultecom/trifecta
```
where ZK_HOST is the url to your Zookeeper instance (e.g. localhost:2181).