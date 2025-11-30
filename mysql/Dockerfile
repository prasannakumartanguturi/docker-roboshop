FROM mysql:8.0
ENV MYSQL_ROOT_PASSWORD="RoboShop@1"
# if w ekeep all our sctpt files /docker-entrypoint-initdb.d in this path then mysql image will take care other things
COPY db/ /docker-entrypoint-initdb.d

