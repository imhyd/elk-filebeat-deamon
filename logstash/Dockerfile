FROM docker.elastic.co/logstash/logstash:6.5.4

RUN rm -f /usr/share/logstash/pipeline/logstash.conf
COPY pipeline /usr/share/logstash/pipeline/
