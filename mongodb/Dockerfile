# FROM mongo:7.0 -> this will pull mongo image from official docker hub,build the image and start the container 
# As per official mongo docker hub doc, we need to keep all scripts in /docker-entrypoint-initdb.d so that it will start the container with those scripts.
# As per roboshop documentation Mondo db instance is to install mongodb and load sql script.

FROM mongo:7.0
COPY *.js /docker-entrypoint-initdb.d