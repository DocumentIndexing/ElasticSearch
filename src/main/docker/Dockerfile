FROM docker.elastic.co/elasticsearch/elasticsearch:6.6.1

COPY maven/elasticsearch/elasticsearch.yml /usr/share/elasticsearch/config/elasticsearch.yml

RUN rm -rf /usr/share/elasticsearch/bin/x-pack
RUN rm -rf /usr/share/elasticsearch/modules/x-pack*

# Define default command
ENTRYPOINT ["/usr/local/bin/docker-entrypoint.sh"]
