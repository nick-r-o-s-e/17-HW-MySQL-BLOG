FROM mysql:latest

COPY setup.sql /docker-entrypoint-initdb.d/

EXPOSE 3306

CMD ["mysqld"]