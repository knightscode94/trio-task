FROM mysql

ENV MYSQL_DATABASE flask-db

COPY ./CreateTable.sql/ /docker-entrypoint-initdb.d/
