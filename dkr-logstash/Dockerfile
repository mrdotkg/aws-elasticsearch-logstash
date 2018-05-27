# set default elk version to 6.1.1
ARG ELK_VERSION=6.1.1

# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash-oss:${ELK_VERSION}

# Add your logstash plugins setup here
RUN logstash-plugin install logstash-filter-json