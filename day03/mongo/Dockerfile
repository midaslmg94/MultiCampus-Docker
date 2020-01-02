FROM mongo:latest

WORKDIR /usr/src
RUN mkdir mongo_config
WORKDIR /usr/src/mongo_config

COPY replication-setting.js .
CMD ["mongo", "mongodb://mongo1:27017", "./replication-setting.js"]