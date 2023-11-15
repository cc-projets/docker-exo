FROM mysql

COPY ./beer.sql /docker-entrypoint-initdb.d

ENV MYSQL_DATABASE=beer
ENV MYSQL_ROOT_PASSWORD=root