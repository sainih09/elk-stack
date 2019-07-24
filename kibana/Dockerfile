ARG ELK_VERSION

# https://github.com/elastic/kibana-docker
FROM docker.elastic.co/kibana/kibana:6.5.4
# RUN /opt/kibana/bin/kibana-plugin install https://github.com/sirensolutions/sentinl/releases/download/tag-6.5.0-0/sentinl-v6.5.4.zip
RUN /opt/kibana/bin/kibana-plugin install https://github.com/bitsensor/elastalert-kibana-plugin/releases/download/1.0.1/elastalert-kibana-plugin-1.0.1-6.5.4.zip
# Add your kibana plugins setup here
# Example: RUN kibana-plugin install <name|url>
