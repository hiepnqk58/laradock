ARG MONGODB_VERSION=latest
FROM mongo:${MONGODB_VERSION}

LABEL maintainer="Mahmoud Zalt <mahmoud@zalt.me>"

#COPY mongo.conf /usr/local/etc/mongo/mongo.conf

VOLUME /data/db /data/configdb

CMD ["mongod"]

EXPOSE 27017

