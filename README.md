# ElasticSearch set up for DocumentIndex

To apply the setting on a live system type:
```
sudo sysctl -w vm.max_map_count=262144
```

For more details see (Virtual Memory)[https://www.elastic.co/guide/en/elasticsearch/reference/current/vm-max-map-count.html]

This extends `docker.elastic.co/elasticsearch/elasticsearch:latest`
primarily to remove the x-pack nonsense :)
