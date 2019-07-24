# ARG ELK_VERSION

FROM docker.elastic.co/beats/filebeat:7.1.1
# FROM docker.elastic.co/beats/filebeat:7.1.1
USER root
COPY ./config/filebeat.yml /usr/share/filebeat/filebeat.yml
RUN chown root:filebeat /usr/share/filebeat/filebeat.yml
RUN chmod go-w /usr/share/filebeat/filebeat.yml