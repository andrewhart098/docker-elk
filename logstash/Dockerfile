# https://github.com/elastic/logstash-docker
FROM docker.elastic.co/logstash/logstash-oss:6.2.2

# Add your logstash plugins setup here
# Example: RUN logstash-plugin install logstash-filter-json
# Enable udp on docker: https://serverfault.com/questions/852475/how-to-forward-udp-packets-from-docker-container-to-host-127-0-0-1
RUN logstash-plugin install logstash-input-syslog
RUN logstash-plugin install logstash-output-syslog
