# ElasticSearch set up for DocumentIndex

To apply the setting on a live system type:
```
sudo sysctl -w vm.max_map_count=262144
```

This extends `docker.elastic.co/elasticsearch/elasticsearch:latest`
primarily to remove the x-pack nonsense :)