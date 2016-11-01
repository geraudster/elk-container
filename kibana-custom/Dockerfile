FROM kibana

RUN kibana plugin --install elastic/sense
RUN kibana plugin --install elastic/timelion
COPY kibana.yml /opt/kibana/config/
