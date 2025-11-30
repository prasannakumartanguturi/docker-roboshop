FROM node:20
WORKDIR /opt/server
COPY package.json .
COPY *.js .
RUN npm install
ENV mongo="true" \
    REDIS_URL='redis://redis:6379'
    MONGO_URL="mongodb://mongodb:27017/users"
# command to run your nodejs application and starts container 
CMD ["node", "server.js"]