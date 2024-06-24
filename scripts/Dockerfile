FROM mysql:latest

ENV MYSQL_ROOT_PASSWORD=rootpassword
ENV MYSQL_DATABASE=BANCO_DADOS_IT_TALENT

COPY dump.sql /docker-entrypoint-initdb.d/

EXPOSE 3306

CMD ["mysqld"]