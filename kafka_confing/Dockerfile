FROM confluentinc/cp-server-connect-base:7.2.1

ENV CONNECT_PLUGIN_PATH="/usr/share/java,/usr/share/confluent-hub-components"

RUN confluent-hub install --no-prompt debezium/debezium-connector-sqlserver:1.9.3
