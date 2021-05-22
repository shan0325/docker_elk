ARG ELK_VERSION

# https://www.docker.elastic.co/
FROM docker.elastic.co/logstash/logstash:${ELK_VERSION}

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json

# http_poller input plugin 설치
RUN logstash-plugin install logstash-input-http_poller
# elasticsearch output plugin 설치
# RUN logstash-plugin install logstash-output-ealsticsearch
