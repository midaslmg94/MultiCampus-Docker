FROM mysql:latest

WORKDIR /usr/src
RUN mkdir mysql_config
WORKDIR /usr/src/mysql_config

COPY replication-setting.js .
CMD ["mysql", "mysqldb://mysql:13306", "./replication-setting.js"]