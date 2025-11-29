# FROM mongo:7.0 -> this will pull mongo image from official docker hub,build the image and start the container 
# As per official mongo docker hub doc, we need to keep all scripts in /docker-entrypoint-initdb.d so that it will start the container with those scripts.

FROM mongo:7.0
COPY server.js /docker-entrypoint-initdb.d