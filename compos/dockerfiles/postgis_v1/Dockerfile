FROM postgres:12

RUN apt-get update && apt-get install postgis -y
# Include datastore setup scripts
COPY ./docker-entrypoint-initdb.d /docker-entrypoint-initdb.d
