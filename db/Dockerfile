FROM mysql:8.0

COPY ./cookdb_authentbl.sql /docker-entrypoint-initdb.d

ENV MYSQL_ROOT_PASSWORD=1234
ENV MYSQL_DATABASE=cookdb