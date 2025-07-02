FROM clickhouse:24.12

COPY ./osc-entrypoint.sh /osc-entrypoint.sh
RUN chmod +x /osc-entrypoint.sh

COPY ./osc-config.xml /etc/clickhouse-server/config.d/osc-config.xml
ENTRYPOINT ["/osc-entrypoint.sh"]