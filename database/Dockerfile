# Use the latest LTS version of Node.js
FROM mariadb:latest

# Variable d'environnement
ENV MARIADB_ROOT_PASSWORD=root
ENV MARIADB_DATABASE=tasksdb

COPY init.sql /docker-entrypoint-initdb.d/

EXPOSE 3306
