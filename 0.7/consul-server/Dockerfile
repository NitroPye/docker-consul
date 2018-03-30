FROM gliderlabs/consul-agent:0.7
RUN apk --update add nagios-plugins
ADD ./config /config/
ENTRYPOINT ["/bin/consul", "agent", "-server", "-config-dir=/config"]
