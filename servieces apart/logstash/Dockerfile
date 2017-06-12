# ELK stack for Virtual-Vehicles Dockerfile
FROM docker.elastic.co/logstash/logstash:5.4.1

COPY logstash.conf /config/logstash.conf

CMD ["-f", "/config/logstash.conf"]